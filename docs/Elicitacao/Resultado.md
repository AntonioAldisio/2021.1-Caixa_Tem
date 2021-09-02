# Resultado Elicitação

## 1. Metodologia
<p style="text-indent: 40px; align="justify"> 
O objetivo desse documento é reunir todos os requistos que foram elicitados para o projeto a partir das técnicas:
</p>

Legenda  

1. IF - Introspecção Funcional
2. BF - Brainstorming Funcional
3. SF - Storytelling Funcional
4. OF - Observação Funcional
5. EF - Entrevistas Funcional
6. QF - Questionário Funcional
7. AF - Analise de Documentos Funcional


<p style="text-indent: 40px; align="justify"> Após discussão com o grupo, decidimos utilizar a técnica de priorização MoSCoW, pois a técnica é mais apropriada para o contexto do aplicativo.<a href="../Priorizacao/moscow/">[1]</a></p> 

## 2. Requisitos Funcionais

<center>

| ID | Requisito | Técnica | <a href="../Priorizacao/moscow/">Priorização</a> | 
|:--:|:--:|:--:|:--:|
| RF 01 | O usuário deve ser capaz de realizar cadastro | <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF01</a>, <a href="../Tecnicas/observacao#ObservaçãoFuncional">OF1</a>, <a href="../Tecnicas/storytelling#StorytellingFuncional">SF01</a> | MUST |
| RF 02 | O usuário deve ser capaz de realizar login | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF01</a>, <a href="../Tecnicas/storytelling#StorytellingFuncional">SF02</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF02</a>, <a href="../Tecnicas/observacao#ObservaçãoFuncional">OF02</a> | MUST |
| RF 03 | O usuário pode realizar pagamentos | <a href="../Tecnicas/storytelling#StorytellingFuncional">SF08</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF03</a> | SHOULD |
| RF 04 | O usuário pode realizar pagamentos via boletos | <a href="../Tecnicas/questionario#QuestionarioFuncional">QF06</a>, <a href="../Tecnicas/entrevista#EntrevistaFuncional">EF06</a>, <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF04</a> | SHOULD |
| RF 05 | O usuário pode realizar pagamentos via PIX | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF05</a>, <a href="../Tecnicas/observacao#ObservaçãoFuncional">OF09</a> | COULD |
| RF 06 | O usuário tem que ser capaz de pagar praticamente qualquer tipo de conta nas Unidades Lotéricas| <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF16</a> | SHOULD |
| RF 07 | O usuário pode consultar saldo | <a href="../Tecnicas/questionario#QuestionarioFuncional">QF02</a>, <a href="../Tecnicas/entrevista#EntrevistaFuncional">EF05</a>, <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF03</a>, <a href="../Tecnicas/storytelling#StorytellingFuncional">SF06</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF04</a>, <a href="../Tecnicas/observacao#ObservaçãoFuncional">OF03</a>  | MUST |
| RF 08 | O usuário pode consultar o extrato | <a href="../Tecnicas/questionario#QuestionarioFuncional">QF03</a>, <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF02</a>, <a href="../Tecnicas/storytelling#StorytellingFuncional">SF07</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF05</a>, <a href="../Tecnicas/observacao#ObservaçãoFuncional">OF04</a>  | MUST |
| RF 09 | O sistema deve gerar cartão de débito virtual | <a href="../Tecnicas/questionario#QuestionarioFuncional">QF08</a>, <a href="../Tecnicas/entrevista#EntrevistaFuncional">EF08</a>, <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF19</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF06</a> | SHOULD | 
| RF 10 | O usuário poderá sacar dinheiro em qualquer caixa eletrônico da caixa.| <a href="../Tecnicas/entrevista#EntrevistaFuncional">EF03</a>, <a href="../Tecnicas/storytelling#StorytellingFuncional">SF09</a>, <a href="../Tecnicas/observacao#ObservaçãoFuncional">OF07</a>  | WOULD | 
| RF 11 | O sistema deve gerar código para saque | <a href="../Tecnicas/questionario#QuestionarioFuncional">QF05</a>, <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF08</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF07</a> | COULD |
| RF 12 | O usuário deve ser capaz de comprar na maquininha com QR code | <a href="../Tecnicas/questionario#QuestionarioFuncional">QF07</a>, <a href="../Tecnicas/entrevista#EntrevistaFuncional">EF07</a>, <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF09</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF08</a> | WOULD |
| RF 13 | O usuário pode consultar informe de rendimentos | <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF09</a> | WOULD |
| RF 14 | O usuário pode realizar transferências | <a href="../Tecnicas/questionario#QuestionarioFuncional">QF01</a>, <a href="../Tecnicas/entrevista#EntrevistaFuncional">EF04</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF10</a>, <a href="../Tecnicas/observacao#ObservaçãoFuncional">OF05</a>, <a href="../Tecnicas/observacao#ObservaçãoFuncional">OF08</a>   | MUST |
| RF 15 | O usuário tem que ser capaz de realizar transferência via TED/DOC  | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF06</a> | MUST |
| RF 16 | O usuário tem que ser capaz de realizar transferência via pix  | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF07</a> | MUST |
| RF 17 | O usuário pode consultar comprovantes | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF20</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF11</a> | MUST |
| RF 18 | O usuário pode receber o seguro desemprego pelo app | <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF12</a> | SHOULD |
| RF 19 | O usuário tem que ser capaz de validar o dispositivo | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF11</a> | COULD |
| RF 20 | O usuário tem que ser capaz de consultar Auxílio Emergencial| <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF12</a> | MUST |
| RF 21 | O usuário tem que ser capaz de consultar BEm | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF13</a> | COULD |
| RF 22 | O usuário tem que ser capaz de consultar FGTS Emergencial | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF14</a> | COULD |
| RF 23 | O usuário tem que ser capaz de consultar Bolsa Família| <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF15</a> | COULD |
| RF 24 | O usuário pode realizar recarga de celular | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF17</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF13</a> | WOULD | 
| RF 25 | O usuário pode fazer recarga de transporte | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF23</a>, <a href="../Tecnicas/brainstorm#BrainstormingFuncional">BF14</a> | WOULD |
| RF 26 | O usuário tem que ser capaz de fazer recarga no aplicativo | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF22</a> | WOULD |
| RF 27 | O usuário tem que ser capaz de acessar as informaçōes do NIS | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF21</a> | COULD |
| RF 28 | O usuário tem que ser capaz de movimentar sua conta poupança social digital na CAIXA | <a href="../Tecnicas/inpeccao#IntrospecçãoFuncional">IF18</a> | COULD |
| RF 30 | O usuário poderá checar se está elegível a receber auxílio emergencial. | <a href="../Tecnicas/storytelling#StorytellingFuncional">SF03</a>, <a href="../Tecnicas/storytelling#StorytellingFuncional">SF10</a> | MUST |
| RF 31 | O usuário pode checar o estado do seu auxílio emergencial. | <a href="../Tecnicas/entrevista#EntrevistaFuncional">EF02</a>, <a href="../Tecnicas/storytelling#StorytellingFuncional">SF04</a>, <a href="../Tecnicas/observacao#ObservaçãoFuncional">OF06</a>  | MUST |
| RF 32 | O usuário deverá ter acesso ao calendário que marca o dia que o seu auxílio será disponibilizado. | <a href="../Tecnicas/storytelling#StorytellingFuncional">SF05</a> | MUST |
| RF 33 | O usuário terá opção de contratar seguro apoio família. | <a href="../Tecnicas/storytelling#StorytellingFuncional">SF11</a> | COULD |
| RF 34 | O usuário terá opção de Selecionar funções favoritas. | <a href="../Tecnicas/entrevista#EntrevistaFuncional">EF01</a> | WOULD |

</center>


## 4. Requisitos Não - Funcionais

<center>

| ID | Requisito |  Técnica | Priorização | 
|:--:|:--:|:--:|:--:|
| RNF 01 | O aplicativo deve ter compatibilidade com qualquer sistema operacional | <a href="../Tecnicas/brainstorm#BrainstormingNFuncional">BNF01</a> | MUST |
| RNF 02 | O sistema deve recusar o acesso de pessoas não autorizadas | <a href="../Tecnicas/inpeccao#IntrospecçãoNFuncional">INF04</a>, <a href="../Tecnicas/brainstorm#BrainstormingNFuncional">BNF02</a>  | MUST |
| RNF 03 | As funcionalidades devem se parecer com uma conversa (chatbot) | <a href="../Tecnicas/questionario#QuestionarioNFuncional">QNF03</a>, <a href="../Tecnicas/storytelling#StorytellingNFuncional">SNF02</a>, <a href="../Tecnicas/brainstorm#BrainstormingNFuncional">BNF04</a>  | COULD |
| RNF 04 | O aplicativo não pode ter grande espaço de armazenamento. | <a href="../Tecnicas/inpeccao#IntrospecçãoNFuncional">INF01</a> | SHOULD |
| RNF 05 | O aplicativo não pode ficar indisponível por mais que 10 minutos por dia. | <a href="../Tecnicas/inpeccao#IntrospecçãoNFuncional">INF02</a>, <a href="../Tecnicas/storytelling#StorytellingNFuncional">SNF03</a>   | MUST |
| RNF 06 | O aplicativo não pode apresentar dados de cunho privativo que não seja do próprio usuário. | <a href="../Tecnicas/inpeccao#IntrospecçãoNFuncional">INF03</a>  | MUST |
| RNF 07 | O usuários devem conseguir encontrar a funcionalidade desejada em menos que três clicks. | <a href="../Tecnicas/inpeccao#IntrospecçãoNFuncional">INF05</a>  | SHOULD |
| RNF 08 | O aplicativo deve se comunicar com o banco de dados.| <a href="../Tecnicas/inpeccao#IntrospecçãoNFuncional">INF06</a>  | MUST |
| RNF 09 | O aplicativo deve proteger os dados dos usuários.| <a href="../Tecnicas/questionario#QuestionarioNFuncional">QNF01</a>, <a href="../Tecnicas/inpeccao#IntrospecçãoNFuncional">INF07</a>, <a href="../Tecnicas/storytelling#StorytellingNFuncional">SNF05</a>  | MUST |
| RNF 10 | O aplicativo deve ser desenvolvido em uma linguagem que tenha uma comunidade ativa e/ou que não tenha previsão de descontinuade da linguagem nos próximos 5 anos.| <a href="../Tecnicas/inpeccao#IntrospecçãoNFuncional">INF08</a>  | SOULD |
| RNF 11 | O usuário não pode ficar mais de 15 minutos em fila para acessar o aplicativo. | <a href="../Tecnicas/storytelling#StorytellingNFuncional">SNF01</a> | SHOULD |
| RNF 12 | O sistema deve ser acessível para Pessoas com Deficiência (PcD) | <a href="../Tecnicas/questionario#QuestionarioNFuncional">QNF02</a>, <a href="../Tecnicas/entrevista#EntrevistaNFuncional">ENF02</a>, <a href="../Tecnicas/brainstorm#BrainstormingNFuncional">BNF03</a> | MUST |
| RNF 13 | 	O código de segurança gerado para realizar compras com cartão de débito virtual deve ser válido para apenas uma compra | <a href="../Tecnicas/questionario#QuestionarioNFuncional">QNF04</a> | MUST |
| RNF 14 | 	Ter a opção de guia para primeiro acesso | <a href="../Tecnicas/entrevista#EntrevistaNFuncional">ENF03</a>, <a href="../Tecnicas/observacao#ObservaçãoNFuncional">ONF01</a>| COULD |

</center>


## Versionamento

<center>

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 13/08/2021 | Criação do página | Antônio Aldisio |
| 1.1 | 20/08/2021 | União do resultados das técnicas de elicitação e priorização | Antônio Aldisio<br>Fernando Calil |
| 1.2 | 01/09/2021 | Adicionada rastreabilidade para técnicas que originaram os requisitos | Fernando Calil |

</center>
