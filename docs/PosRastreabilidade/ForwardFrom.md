# Matriz Forward-From

## 1. Introdução

<p style="text-indent: 40px; align="justify">Rastreabilidade é uma característica de sistemas, nos quais requisitos são claramente ligados às
suas fontes bem como aos artefatos criados durante o ciclo de vida de desenvolvimento do sistema. Pode ser dividida em Pré-Rastreabilidade e Pós-Rastreabilidade.</p>
<p style="text-indent: 40px; align="justify">A Pós-Rastreabilidade consiste em requisitos sendo ligados a artefatos que são criados durante o ciclo de vida de
desenvolvimento do sistema.</p>
<p style="text-indent: 40px; align="justify">A técnica de Pós-Rastreabilidade Forward-Form visa ligar requisitos a artefatos de desenho 
e implementação.<a href="#Bibliografia">[1]</a><br></p>

## 2. Requisitos Funcionais
<center>

| ID | Requisito | Cenários | Léxicos | Casos de Uso | Histórias de Usuário |
|:-:|--|:-:|:-:|:-:|:-:|
| RF 01 | O usuário deve ser capaz de realizar cadastro |-|-|-|-|
| RF 02 | O usuário deve ser capaz de realizar login |-|-|-|-|
| RF 03 | O usuário pode realizar pagamentos |-|-|-|-|
| RF 04 | O usuário pode realizar pagamentos via boletos |-|-|-|-|
| RF 05 | O usuário pode realizar pagamentos via PIX |-|-|-|-|
| RF 06 | O usuário tem que ser capaz de pagar praticamente qualquer tipo de conta nas Unidades Lotéricas |-|-|-|-|
| RF 07 | O usuário pode consultar saldo |-|-|-|-|
| RF 08 | O usuário pode consultar o extrato |-|-|-|-|
| RF 09 | O sistema deve gerar cartão de débito virtual |-|-|-|-|
| RF 10 | O usuário poderá sacar dinheiro em qualquer caixa eletrônico da caixa |-|-|-|-|
| RF 11 | O sistema deve gerar código para saque |-|-|-|-|
| RF 12 | O usuário deve ser capaz de comprar na maquininha com QR code |-|-|-|-|
| RF 13 | O usuário pode consultar informe de rendimentos |-|-|-|-|
| RF 14 | O usuário pode realizar transferências |-|-|-|-|
| RF 15 | O usuário tem que ser capaz de realizar transferência via TED/DOC  |-|-|-|-|
| RF 16 | O usuário tem que ser capaz de realizar transferência via pix |-|-|-|-| 
| RF 17 | O usuário pode consultar comprovantes |-|-|-|-|
| RF 18 | O usuário pode receber o seguro desemprego pelo app |-|-|-|-|
| RF 19 | O usuário tem que ser capaz de validar o dispositivo |-|-|-|-|
| RF 20 | O usuário tem que ser capaz de consultar Auxílio Emergencial |-|-|-|-|
| RF 21 | O usuário tem que ser capaz de consultar BEm |-|-|-|-|
| RF 22 | O usuário tem que ser capaz de consultar FGTS Emergencial |-|-|-|-|
| RF 23 | O usuário tem que ser capaz de consultar Bolsa Família |-|-|-|-|
| RF 24 | O usuário pode realizar recarga de celular |-|-|-|-|
| RF 25 | O usuário pode fazer recarga de transporte |-|-|-|-|
| RF 26 | O usuário tem que ser capaz de fazer recarga no aplicativo |-|-|-|-|
| RF 27 | O usuário tem que ser capaz de acessar as informaçōes do NIS |-|-|-|-|
| RF 28 | O usuário tem que ser capaz de movimentar sua conta poupança social digital na CAIXA |-|-|-|-|
| RF 30 | O usuário poderá checar se está elegível a receber auxílio emergencial. |-|-|-|-| 
| RF 31 | O usuário pode checar o estado do seu auxílio emergencial. |-|-|-|-|
| RF 32 | O usuário deverá ter acesso ao calendário que marca o dia que o seu auxílio será disponibilizado |-|-|-|-|
| RF 33 | O usuário terá opção de contratar seguro apoio família |-|-|-|-|
| RF 34 | O usuário terá opção de Selecionar funções favoritas |-|-|-|-|

</center>


## 3. Requisitos Não - Funcionais

<center>

| ID | Requisito | Léxicos | NFR | Especificação Suplementar |
|:-:|--|:-:|:-:|:-:|
| RNF 01 | O aplicativo deve ter compatibilidade com qualquer sistema operacional |-|[Eficiência](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|[Suportabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#34-suportabilidade)| 
| RNF 02 | O sistema deve recusar o acesso de pessoas não autorizadas |[L09](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l09-login)|[Eficiência](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|-| 
| RNF 03 | As funcionalidades devem se parecer com uma conversa (chatbot) |-|[Eficácia](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#321-diagrama-nfr-com-propagacao-da-eficacia) |[Usabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#31-usabilidade)| 
| RNF 04 | O aplicativo não pode ter grande espaço de armazenamento. |-|-|[Desempenho](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#33-desempenho)|
| RNF 05 | O aplicativo não pode ficar indisponível por mais que 10 minutos por dia. |-|[Satisfação](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-satisfacao)|[Disponibilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#321-disponibilidade)| 
| RNF 06 | O aplicativo não pode apresentar dados de cunho privativo que não seja do próprio usuário. |[L01](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l01-conta)|[Eficiência](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|[Privacidade dos Dados](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#322-privacidade-dos-dados)| 
| RNF 07 | O usuários devem conseguir encontrar a funcionalidade desejada em menos que três clicks. |-|[Satisfação](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-satisfacao)|[Usabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#31-usabilidade)|
| RNF 08 | O aplicativo deve se comunicar com o banco de dados.|-|[Segurança](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|-| 
| RNF 09 | O aplicativo deve proteger os dados dos usuários.|[L01](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l01-conta)|[Eficiência](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|[Privacidade dos Dados](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#322-privacidade-dos-dados)| 
| RNF 10 | O aplicativo deve ser desenvolvido em uma linguagem que tenha uma comunidade ativa e/ou que não tenha previsão de descontinuade da linguagem nos próximos 5 anos.|-|[Disponibilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-satisfacao)|-| 
| RNF 11 | O usuário não pode ficar mais de 15 minutos em fila para acessar o aplicativo. |-|[Satisfação](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-satisfacao)|-|
| RNF 12 | O sistema deve ser acessível para Pessoas com Deficiência (PcD) |-|[Acessibilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#321-diagrama-nfr-com-propagacao-da-eficacia)|[Usabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#31-usabilidade)| 
| RNF 13 | 	O código de segurança gerado para realizar compras com cartão de débito virtual deve ser válido para apenas uma compra |-|[Segurança](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|-| 
| RNF 14 | 	Ter a opção de guia para primeiro acesso |-|[Eficácia](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#321-diagrama-nfr-com-propagacao-da-eficacia)|[Usabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#31-usabilidade)| 

</center>

## 4. Bibliografia <a id="Bibliografia"></a>
<p align = "justify"> [1] SERRANO, Maurício; SERRANO, Milene. <strong>Requisitos - Aula 26</strong>. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.</p>

## Versionamento
<center>

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 05/10/2021 | Criação do página | Lucas Gomes |
| 2.0 | 07/10/2021 | Adição da Matriz | Lucas Gomes |
| 3.0 | 07/10/2021 | Adição co conteúdo da matriz de requisitos não-funcionais | Lucas Gomes |


</center>