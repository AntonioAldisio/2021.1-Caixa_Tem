# NFR Framework

## 1. Introdução
<p style="text-indent: 40px; align="justify">Existem muitas formas de se representar e analisar requisitos não funcionais (NFR), dentre elas vale citar as árvores de qualidade de software, a técnica FURPS +, e a classificação feita pela “standard ISO/IEC 9126”. Essas classificações são úteis para a questão de análise de NFR, entretanto, há uma falta de consistência entre elas.</p>
<p style="text-indent: 40px; align="justify">No artigo escrito pelos cientistas da computação Lawrence Chung e Julio Cesar Sampaio do Prado, em que é descrito o NFR Framework, eles argumentam sobre como alguns aspectos são tratados de forma diferente entre essas técnicas clássicas, mas sem uma concordância entre elas. O principal diferencial do NFR Framework é descrever um procedimento consistente para modelar os NFR elicitados em uma unidade denominada “Softgoal”, e analisar esses softgoals e suas relações de maneira que a equipe de desenvolvimento pode determinar se os softgoals foram satisfeitos ou não.<a href="../NFR_Framework#Bibliografia">[1]</a><br></p>

## 2. Softgoals

<p style="text-indent: 40px; align="justify">Utilizado pelo NFR Framework, um softgoal é um objetivo que não possui uma clara definição nem critérios de satisfação precisos. Os softgoals são utilizados para representar Requisitos Não-Funcionais e podem estar inter-relacionados, expressando a influência de
um softgoal em outro.<a href="../NFR_Framework#Bibliografia">[2]</a><br></p>
<p style="text-indent: 40px; align="justify">Existem 3 tipos de softgoals. São eles:</p>
<ul style="margin-left:50px">
    <li><strong>Softgoals NFR :</strong> representam os Requisitos Não- Funcionais e podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica no desenvolvimento do projeto (CHUNG et al., 2000).</li>
    <li><strong>Softgoals de Operacionalização :</strong> representam soluções de implementação para
    satisfazer softgoals NFR ou outros softgoals de operacionalização (CHUNG et al., 2000).</li>
    <li><strong>Softgoals de Afirmação :</strong> permitem que as características do domínio (como prioridades e carga de trabalho) sejam consideradas e devidamente refletidas no processo de tomada de decisão.  (CHUNG et al., 2000).</li>
</ul>

<center>
<img src="../../assets/imgs/tiposSoftgoals.png" alt="Tipos de Softgoals">
<figcaption> Figura 01 - Tipos de Softgoals <a href="../NFR_Framework#Bibliografia">[2]</a></figcaption>
</center>

<p style="text-indent: 40px; align="justify">É possível utilizar, no NFR Framwork, diversos tipos de contribuições para descrever como a satisfação ou não de um softgoal descendente irá contribuir para a satisfação do softgoal ascendente.<a href="../NFR_Framework#Bibliografia">[2]</a> Os tipos de contribuição são:<br></p>

Contribuição | Descrição
-|-
AND | Estabelece que os softgoals ascendentes serão satisfeitos se os softgoals descendentes forem satisfeitos.
OR | Se algum softgoal descendente for satisfeito, então o ascendente também será.
MAKE(++) | Fornece uma contribuição suficientemente positiva entre um softgoal descendente e um ascendente.
BREAK(--) | Fornece uma contribuição suficientemente negativa entre um softgoal descendente e um ascendente.
HELP(+) | Fornece uma contribuição parcialmente positiva entre um softgoal descendente e um ascendente.
HURT(-) | Fornece uma contribuição parcialmente negativa entre um softgoal descendente e um ascendente.
UNKNOWN(?) | Fornece uma contribuição desconhecida entre um softgoal descendente e um ascendente.
EQUALS | O softgoal descendente será satisfeito somente se o softgoal ascendente for satisfeito e o softgoal descendente será negado se o ascendente for negado.
SOME (+\|-) | Utilizada quando o sinal de contribuição é conhecido,mas a extensão não é.

<p style="text-indent: 40px; align="justify">O procedimento de avaliação determina o grau que os requisitos não funcionais são satisfeitos por um conjunto de decisões. Para isso, são atribuídos rótulos para os softgoals.<a href="../NFR_Framework#Bibliografia">[2]</a><br></p>

<center>
<img src="../../assets/imgs/rotulosSoftgoals.png" alt="Rótulos de Softgoals">
<figcaption> Figura 02 - Tipos de rótulos utilizados pelos Softgoals <a href="../NFR_Framework#Bibliografia">[2]</a></figcaption>
</center>

## 3. NFR e os Softgoals
<center>

<p style="text-indent: 40px; align="justify">Segue abaixo uma relação dos softgoals referentes aos requisitos não funcionais elicitados para o projeto.</p>

| ID | Requisito | Softgoal equivalente | 
|:--:|:--:|:--:|:--:|
| RNF 01 | O aplicativo deve ter compatibilidade com qualquer sistema operacional | Portabilidade |
| RNF 02 | O sistema deve recusar o acesso de pessoas não autorizadas | Segurança |
| RNF 03 | As funcionalidades devem se parecer com uma conversa (chatbot) | Acessibilidade |
| RNF 04 | O aplicativo não pode ter grande espaço de armazenamento. | Desempenho |
| RNF 05 | O aplicativo não pode ficar indisponível por mais que 10 minutos por dia. | Disponibilidade |
| RNF 06 | O aplicativo não pode apresentar dados de cunho privativo que não seja do próprio usuário. | Segurança |
| RNF 07 | O usuários devem conseguir encontrar a funcionalidade desejada em menos que três clicks. | Usabilidade |
| RNF 08 | O aplicativo deve se comunicar com o banco de dados.| Usabilidade e Segurança |
| RNF 09 | O aplicativo deve proteger os dados dos usuários.| Segurança |
| RNF 10 | O aplicativo deve ser desenvolvido em uma linguagem que tenha uma comunidade ativa e/ou que não tenha previsão de descontinuade da linguagem nos próximos 5 anos.| Portabilidade e Disponibilidade |
| RNF 11 | O usuário não pode ficar mais de 15 minutos em fila para acessar o aplicativo. | Desempenho |
| RNF 12 | O sistema deve ser acessível para Pessoas com Deficiência (PcD) | Acessibilidade |
| RNF 13 |  O código de segurança gerado para realizar compras com cartão de débito virtual deve ser válido para apenas uma compra | Segurança |
| RNF 14 |  Ter a opção de guia para primeiro acesso | Acessibilidade |

</center>

## Bibliografia <a id="Bibliografia"></a>
[1] CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-functional requirements
in software engineering. Springer Science & Business Media: [s.n.], 2000. v. 5. Disponível <a href="http://www-di.inf.puc-rio.br/~julio/nfr-chung-leite.pdf">aqui.</a> Acessado em 03/09/21. 

[2] DA SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019. Dissertação (Mestrado em Ciência da Computação) - Universidade Federal de Pernambuco, Recife, 2019.

## Versionamento

<center>

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 03/09/2021 | Criação da págia e Introdução | Ariel Serafim |
| 2.0 | 04/09/2021 | Melhoria no layout e adição dos tipos de softgoals | Lucas Gomes |
| 3.0 | 04/09/2021 | Adição dos tipos de contribuição e tipos de rótulos | Lucas Gomes |
| 4.0 | 09/09/2021 | Adição da tabela relacionando NFR e softgoals | Ariel Serafim |

</center>