# Matriz Forward-From

## 1. Introdução

<p style="text-indent: 40px; align="justify">Rastreabilidade é uma característica de sistemas, nos quais requisitos são claramente ligados às
suas fontes bem como aos artefatos criados durante o ciclo de vida de desenvolvimento do sistema. Um elo é estabelecido entre as mudanças realizadas diante das necessidades dos usuários.Pode ser dividida em Pré-Rastreabilidade e Pós-Rastreabilidade.</p>
<p style="text-indent: 40px; align="justify">A Pós-Rastreabilidade consiste em requisitos sendo ligados a artefatos que são criados durante o ciclo de vida de
desenvolvimento do sistema.</p>
<p style="text-indent: 40px; align="justify">A técnica de Pós-Rastreabilidade Forward-Form visa ligar requisitos a artefatos de desenho 
e implementação.<a href="#Bibliografia">[1]</a><br></p>

### 1.1 Elos de Rastreabilidade

<p style="text-indent: 40px; align="justify">Os elos de rastreabilidade deixam evidentes as correlações entre código e demais
artefatos, sejam de desenho e/ou de requisitos.</p>
<p style="text-indent: 40px; align="justify">O Meta-modelo de Toranzo permite debater sobre os elos de rastreabilidade. Nesse modelo, as informações a serem rastreadas devem ser classificadas em quatro níveis: <a href="#Bibliografia">[1]</a></p>
<p style="text-indent: 40px; align="justify">
<ul>
    <li><strong>Ambiental:</strong> informações oriundas do contexto no qual a organização está inserida;</li>
    <li><strong>Organizacional:</strong> informações pertencentes à organização (missão, objetivos e estratégias);</li>
    <li><strong>Gerencial:</strong> informações que auxiliam a gerência do projeto;</li>
    <li><strong>Desenvolvimento:</strong> informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (artefatos de requisitos, diagramas, códigos, casos de teste e outros).</li>
</ul>
</p>

<p style="text-indent: 40px; align="justify">E os principais elos de rastreabilidade são: <a href="#Bibliografia">[1]</a></p>
<p style="text-indent: 40px; align="justify">
<ul>
    <li><strong>Satisfação::</strong> classe origem tem dependência de satisfação com a classe destino.</li>
    <li><strong>Recurso:</strong> classe origem tem dependência de recurso com a classe destino.</li>
    <li><strong>Responsabilidade:</strong> registra a participação, responsabilidade e ação de pessoas sobre artefatos.</li>
    <li><strong>Representação:</strong> captura a representação ou modelagem dos requisitos em outras linguagens.</li>
    <li><strong>Alocado:</strong> classe origem está relacionada à classe destino, que representa um subsistema.</li>
    <li><strong>Agregação:</strong>  indica “composição” de elementos.</li>

</ul>
</p>
## 2. Requisitos Funcionais
<center>

|ID|Requisito|Cenários|Léxicos|Casos de Uso|Histórias de Usuário|Categoria|Elo|
|-|--|-|-|-|-|-|-|
| RF 01 | O usuário deve ser capaz de realizar cadastro |[C01](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c01-cadastro) |[L01](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l01-conta)|[3.1](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#31-fluxo-basico)|[USO1](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US01/)|Organizacional, Desenvolvimento|Recurso, Satisfação|
| RF 02 | O usuário deve ser capaz de realizar login |[C02](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c02-login)|[L09](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l09-login)|[3.1](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#31-fluxo-basico)|[USO2](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US02/)|Organizacional, Desenvolvimento|REcurso, Satisfação|
| RF 03 | O usuário pode realizar pagamentos |[C13 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c13-gerar-codigo-para-pagar-contas-na-loterica)[C14 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c14-utilizar-cartao-de-debito-virtual)[C16 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c16-realizar-pagamentos-com-boleto)[C17 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c17-realizar-pagamentos-com-pix)|[L06](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l06-pix)|[3.2.2 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#322-pagar-na-maquininha)[3.2.3 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#323-cartao-de-debito-virtual)[3.2.6 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#326-realizar-pagamentos)[3.2.7 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#327-pix)|[USO15 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US015/)[USO16 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US016/)[USO17 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US017/)[USO18 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US018/)[USO19 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US019/)[USO20 ](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US020/)|Desenvolvimento|Satisfação, Agregação, Responsabilidade|
| RF 04 | O usuário pode realizar pagamentos via boletos |[C16](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c16-realizar-pagamentos-com-boleto)|-|[3.2.6](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#326-realizar-pagamentos)|[USO18](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US018/)|Desenvolvimento|Satisfação, Responsabilidade|
| RF 05 | O usuário pode realizar pagamentos via PIX |[C17](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c17-realizar-pagamentos-com-pix)|[L06](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l06-pix)|[3.2.7](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#327-pix)|[USO15](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US015/)|Desenvolvimento|Satisfação, Responsabilidade|
| RF 06 | O usuário tem que ser capaz de pagar praticamente qualquer tipo de conta nas Unidades Lotéricas |[C13](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c13-gerar-codigo-para-pagar-contas-na-loterica)|-|-|[USO19](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US019/)|Desenvolvimento|Satisfação, Responsabilidade|
| RF 07 | O usuário pode consultar saldo |[C09](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c09-consultar-saldo)|[L07](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l06-pix)|[3.2.2](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#322-pagar-na-maquininha)|[USO11](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US011/)|Gerencial, Desenvolvimento|Satisfação, Responsabilidade|
| RF 08 | O usuário pode consultar o extrato |[C03](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c03-extrato)|[L04](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l04-extrato)|[3.2.1](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#321-extrato)|[USO10](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US010/)|Gerencial, Desenvolvimento|Satisfação, Responsabilidade|
| RF 09 | O sistema deve gerar cartão de débito virtual |[C14](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c14-utilizar-cartao-de-debito-virtual)|-|[3.2.3](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#323-cartao-de-debito-virtual)|[USO17](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US017/)|Ambiental, Organizacional, Desenvolvimento|Satisfação|
| RF 10 | O usuário poderá sacar dinheiro em qualquer caixa eletrônico da caixa |[C15](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c15-gerar-codigo-para-saque-sem-cartao)|-|[3.2.4](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#324-saque-sem-cartao)|[USO22](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US022/)|Ambiental, Organizacional, Desenvolvimento|Responsabilidade|
| RF 11 | O sistema deve gerar código para saque |[C15](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c15-gerar-codigo-para-saque-sem-cartao)|[L05](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l05-saque)|[3.2.4](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#324-saque-sem-cartao)|[USO22](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US022/)|Organizacional, Desenvolvimento|Satisfação|
| RF 12 | O usuário deve ser capaz de comprar na maquininha com QR code |-|-|[3.2.2](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#322-pagar-na-maquininha)|[USO20](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US020/)|Ambiental, Organizacional|Responsabilidade, Satisfação|
| RF 13 | O usuário pode consultar informe de rendimentos |[C05](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c06-consultar-programas-sociais)|[L08](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l08-rendimento)|-|[US014](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US014/)|Gerencial, Desenvolvimento|Satisfação, Representação|
| RF 14 | O usuário pode realizar transferências |[C10](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c10-realizar-transferencias)|[L11](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l11-transferir)|[3.2.5](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#325-transferir-dinheiro)|[US016](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US016/)[US015](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US015/)|Gerencial, Desenvolvimento|Responsabilidade, Satisfação|
| RF 15 | O usuário tem que ser capaz de realizar transferência via TED/DOC  |-|[L11](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l11-transferir)|[3.2.5](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#325-transferir-dinheiro)|[US016](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US016/)|Ambiental, Desenvolvimento|Responsabilidade, Satisfação|
| RF 16 | O usuário tem que ser capaz de realizar transferência via pix |[C17](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c17-realizar-pagamentos-com-pix)|[L06](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l06-pix)|[3.2.7](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/CasoUso/#327-pix)|[US015](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US015/)|Ambiental, Desenvolvimento|Responsabilidade, Satisfação|
| RF 17 | O usuário pode consultar comprovantes |[C07](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c07-consultar-comprovantes)|[L02](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l02-comprovante)|-|[US012](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US012/)|Gerencial, Desenvolvimento, Organizacional|Responsabilidade, Satisfação|
| RF 18 | O usuário pode receber o seguro desemprego pelo app |[L03](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l03-seguro)|-|-|-|Gerencial, Desenvolvimento|Responsabilidade, Satisfação, Representação|
| RF 19 | O usuário tem que ser capaz de validar o dispositivo |-|-|-|[US04](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US04/)|Gerencial, Desenvolvimento|Recurso|
| RF 20 | O usuário tem que ser capaz de consultar Auxílio Emergencial |[C06](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c06-consultar-programas-sociais)|-|-|[US06](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US06/)|Desenvolvimento, Organizacional|Satisfação, Responsabilidade|
| RF 21 | O usuário tem que ser capaz de consultar BEm |[C06](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c06-consultar-programas-sociais)|-|-|[US07](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US07/)|Gerencial, Desenvolvimento|Satisfação, Responsabilidade|
| RF 22 | O usuário tem que ser capaz de consultar FGTS Emergencial |-|-|-|[US08](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US08/)|Gerencial, Desenvolvimento|Satisfação, Responsabilidade|
| RF 23 | O usuário tem que ser capaz de consultar Bolsa Família |[C06](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c06-consultar-programas-sociais)|-|-|-|Gerencial, Desenvolvimento|Satisfação, Responsabilidade|
| RF 24 | O usuário pode realizar recarga de celular |[C08](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c08-recarga-de-celular)|-|-|[US024](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US024/)|Ambiental, Desenvolvimento|Responsabilidade, Satisfação|
| RF 25 | O usuário pode fazer recarga de transporte |[C11](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c11-fazer-recarga-de-transporte)|[L02](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l02-comprovante),|-|-|Ambiental, Desenvolvimento|Responsabilidade, Satisfação|
| RF 26 | O usuário tem que ser capaz de fazer recarga no aplicativo |[C08](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c08-recarga-de-celular)|-|-|-|Ambiental, Desenvolvimento|Responsabilidade, Satisfação|
| RF 27 | O usuário tem que ser capaz de acessar as informaçōes do NIS |[C06](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c06-consultar-programas-sociais)|-|-|-|Gerencial, Desenvolvimento|Responsabilidade, Satisfação|
| RF 28 | O usuário tem que ser capaz de movimentar sua conta poupança social digital na CAIXA |[C01](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c01-cadastro) [C02](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c02-login) |[L01](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l01-conta)|-|[US03](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US03/)|Organizacional, Desenvolvimento, Gerencial|Responsabilidade|
| RF 29 | O usuário poderá checar se está elegível a receber auxílio emergencial. |-|-|-|[US05](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US05/)|Gerencial, Desenvolvimento|Recurso| 
| RF 30 | O usuário pode checar o estado do seu auxílio emergencial. |[C06](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c06-consultar-programas-sociais)|-|-|[US05](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US05/)|Gerencial, Desenvolvimento|Satisfação, Responsabilidade|
| RF 31 | O usuário deverá ter acesso ao calendário que marca o dia que o seu auxílio será disponibilizado |[C04](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c04-calendario-do-auxilio-emergencial)|-|-|[US05](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Agil/Historia/US05/)|Organizacional, Desenvolvimento|Satisfação|
| RF 32 | O usuário terá opção de contratar seguro apoio família |[C12](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Cenarios/#c12-contratar-seguro-apoio-familia)|-|-|-|Gerencial, Desenvolvimento|Responsabilidade, Satisfação|
| RF 33 | O usuário terá opção de Selecionar funções favoritas |-|-|-|-|Organizacional, Gerencial, Desenvolvimento|Satisfação|

</center>


## 3. Requisitos Não - Funcionais

<center>

|ID|Requisito|Léxicos|NFR|Especificação Suplementar|Categoria|Elo|
|-|--|-|-|-|-|-|
| RNF 01 | O aplicativo deve ter compatibilidade com qualquer sistema operacional |-|[Eficiência](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|[Suportabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#34-suportabilidade)|Gerencial|Satisfação|
| RNF 02 | O sistema deve recusar o acesso de pessoas não autorizadas |[L09](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l09-login)|[Eficiência](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|-|Gerencial|Responsabilidade| 
| RNF 03 | As funcionalidades devem se parecer com uma conversa (chatbot) |-|[Eficácia](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#321-diagrama-nfr-com-propagacao-da-eficacia) |[Usabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#31-usabilidade)|Gerencial, Desenvolvimento|Satisfação|
| RNF 04 | O aplicativo não pode ter grande espaço de armazenamento. |-|-|[Desempenho](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#33-desempenho)|Desenvolvimento|Recurso, Satisfação|
| RNF 05 | O aplicativo não pode ficar indisponível por mais que 10 minutos por dia. |-|[Satisfação](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-satisfacao)|[Disponibilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#321-disponibilidade)|Gerencial, Desenvolvimento|Satisfação|
| RNF 06 | O aplicativo não pode apresentar dados de cunho privativo que não seja do próprio usuário. |[L01](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l01-conta)|[Eficiência](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|[Privacidade dos Dados](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#322-privacidade-dos-dados)|Ambiental|Responsabilidade| 
| RNF 07 | O usuários devem conseguir encontrar a funcionalidade desejada em menos que três clicks. |-|[Satisfação](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-satisfacao)|[Usabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#31-usabilidade)|Organizacional, Desenvolvimento|Satisfação|
| RNF 08 | O aplicativo deve se comunicar com o banco de dados.|-|[Segurança](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|-|Gerencial, Desenvolvimento|Responsabilidade|
| RNF 09 | O aplicativo deve proteger os dados dos usuários.|[L01](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Lexicos/#l01-conta)|[Eficiência](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|[Privacidade dos Dados](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#322-privacidade-dos-dados)|Ambiental|Responsabilidade, Satisfação| 
| RNF 10 | O aplicativo deve ser desenvolvido em uma linguagem que tenha uma comunidade ativa e/ou que não tenha previsão de descontinuade da linguagem nos próximos 5 anos.|-|[Disponibilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-satisfacao)|-|Gerencial|Responsabilidade|
| RNF 11 | O usuário não pode ficar mais de 15 minutos em fila para acessar o aplicativo. |-|[Satisfação](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-satisfacao)|-|Gerencial, Desenvolvimento|Responsabilidade|
| RNF 12 | O sistema deve ser acessível para Pessoas com Deficiência (PcD) |-|[Acessibilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#321-diagrama-nfr-com-propagacao-da-eficacia)|[Usabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#31-usabilidade)|Gerencial, Desenvolvimento|Satisfação|
| RNF 13 | 	O código de segurança gerado para realizar compras com cartão de débito virtual deve ser válido para apenas uma compra |-|[Segurança](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#322-diagrama-nfr-com-propagacao-da-eficiencia)|-|Ambiental, Desenvolvimento|Responsabilidade|
| RNF 14 | 	Ter a opção de guia para primeiro acesso |-|[Eficácia](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/NFR_Framework/#321-diagrama-nfr-com-propagacao-da-eficacia)|[Usabilidade](https://requisitos-de-software.github.io/2021.1-Caixa_Tem/Modelagem/Especificacao/#31-usabilidade)|Organizacional, Desenvolvimento|Satisfação|

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
| 4.0 | 19/10/2021 | Adição dos elos de rastreabilidade | Lucas Gomes |


</center>
