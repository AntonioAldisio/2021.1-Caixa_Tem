# Cenários

## 1. Introdução

<p style="text-indent: 40px; align="justify"> Cenários são descrições de situações comuns ao cotidiano e que devem levar em conta os aspectos de usabilidade e permitir o aprofundamento do conhecimento do problema, a unificação de critérios, a obtenção do compromisso de clientes e/ou usuários, a organização de detalhes e o treinamento de pessoas.</p>
<p style="text-indent: 40px; align="justify">Cada cenário descreve, através de linguagem natural semi-estruturada, uma situação específica de uma aplicação de software, priorizando seu comportamento.<a href="#Bibliografia">[1]</a><br></p>

## 2. Cenários

<center>

### C01: Cadastro <a id="#cadastro"></a>
| **Título**| Cadastro |
|--|--|
| **Objetivo**| <ul><li>Criar conta de usuário.</li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela inicial da aplicação</li><li>Tempo - A qualquer momento.</li><li>Pré-condições:<ul><li>Ter aplicativo instalado.</li><li>Ter acesso a internet</li></ul></li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema.</li></ul> |
| <br><br><br>**Recursos**| <ul><li>Smartphone</li><li>Acesso a Internet</li><li>CPF</li><li>Email</li><li>Numero de telefone</li><li>CEP</li></ul> |
| <br><br><br><br><br><br><br><br>**Episódios**| <ul><li>Usuário insere CPF.</li><li>Usuário Confirma ação.</li><li>Usuário escolhe opção de cadastro.</li><li>Usuário insere CPF.</li><li>Usuário insere nome completo.</li><li>Usuário insere telefone.</li><li>Usuário confirma telefone</li><li>Usuário insere data de nascimento.</li><li>Usuário insere CEP</li><li>Usuário insere email.</li><li>Usuário confirma email</li><li>Usuário insere senha</li><li>Usuário confirma senha</li><li>Usuário marca o campo captcha.</li><li>Usuário finaliza cadastro.</li></ul> |
| **Restrição**| <ul><li>Usuário deve ter documentação válida.</li></ul> |
| <br><br>**Exceção**| <ul><li>Usuário perde acesso a Internet.</li><li>Smartphone está sem bateria.</li><li>Usuário não informa os dados corretos.</li><li>Usuário não marca campo captcha.</li></ul> |

### C02: Login<a id="login"></a>
| **Título**| Login |
|--|--|
| **Objetivo**| <ul><li>Autenticar o usuário no sistema.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela inicial do aplicativo.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário não pode estar Logado do aplicativo.<br></li></ul>|
| **Atores**| <ul><li>Usuário.</li></ul> |
| **Recursos**| <ul><li><a href="#cadastro">Conta no aplicativo</a></li></ul> |
| <br><br><br>**Episódios**| <ul><li>Usuário abre o aplicativo.</li><li>Usuário insere CPF.</li><li>Usuário confirma ação.</li><li>Usuário insere CPF.</li><li>Usuário insere senha.</li><li>Usuário confirma ação.</li></ul> |
| **Restrição**| <ul><li>Usuário deve possuir <a href="#cadastro">cadastro.</a></li></ul> |
| <br>**Exceção**| <ul><li>Usuário perde acesso a Internet.</li><li>Smartphone está sem bateria.</li><li>Usuário não informa os dados corretos.</li></ul> |


### C03: Extrato<a id="extrato"></a>
| **Título**| Extrato |
|--|--|
| **Objetivo**| <ul><li>Verificar as transações realizadas na conta.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário deve estar <a href="login">logado</a>.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema.</li></ul> |
| **Recursos**| <ul><li><a href="#cadastro">Conta no aplicativo</a>.</li></ul> |
| **Episódios**| <ul><li>Usuário seleciona a funcionalidade de extrato.</li><li>Usuário seleciona o período desejado.</li></ul> |
| **Restrição**| <ul><li>Usuário deve possuir <a href="#cadastro">cadastro.</a></li><li>Usuário deve estar <a href="login">logado</a>.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |


### C04: Calendário do auxílio emergencial<a id="calendario"></a>
| **Título**| Calendário do auxílio emergencial |
|--|--|
| **Objetivo**| <ul><li>Consultar calendário de liberação do auxílio emergencial.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário deve estar <a href="login">logado</a>.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema.</li></ul> |
| **Recursos**| <ul><li><a href="#cadastro">Conta no aplicativo</a></li></ul> |
| **Episódios**| <ul><li>Usuário seleciona a opção de transferência.</li><li>Usuário escolhe a opção Ver calendário.</li></ul> |
| **Restrição**| <ul><li>Usuário deve possuir <a href="#cadastro">cadastro.</a></li><li>Usuário deve estar <a href="login">logado</a>.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C05: Informe de Rendimentos<a id="rendimento"></a>
| **Título**| Informe de Rendimentos |
|--|--|
| **Objetivo**| <ul><li>Consultar os rendimentos da conta pra declaração de imposto.</li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário deve estar <a href="login">logado</a>.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema.</li></ul> |
| **Recursos**| <ul><li><a href="#cadastro">Conta no aplicativo</a>.</li></ul> |
| **Episódios**| <ul><li>Usuário escole a opção Informe de Rendimentos.</li><li>Usuário seleciona Ver informe de Rendimentos</li></ul> |
| **Restrição**| <ul><li>Usuário deve possuir <a href="#cadastro">cadastro.</a></li><li>Usuário deve estar <a href="login">logado</a>.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |


### C06: Consultar Programas Sociais<a id="sociais"></a>
| **Título**| Consultar Programas Sociais |
|--|--|
| **Objetivo**| <ul><li>Consultar situação do programa social desejado.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário deve estar <a href="login">logado</a>.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema.</li></ul> |
| <br>**Recursos**| <ul><li><a href="#cadastro">Conta no aplicativo</a>.</li><li>Elegibilidade para programa social.</li><li>NIS</li></ul> |
| **Episódios**| <ul><li>Usuário escolhe o programa social desejado.</li></ul> |
| **Restrição**| <ul><li>Usuário deve estar <a href="login">logado</a>.</li><li>Usuário deve ser elegível para o benefício social.</li></ul> |
| <br>**Exceção**| <ul><li>Usuário não possui NIS.</li><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C07: Consultar Comprovantes<a id="comprovantes"></a>
| **Título**| Consultar Comprovantes |
|--|--|
| **Objetivo**| <ul><li>Verificar comprovação de transações realizadas pela conta.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário deve estar <a href="login">logado</a>.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema.</li></ul> |
| **Recursos**| <ul><li><a href="#cadastro">Conta no aplicativo</a></li></ul> |
| <br>**Episódios**| <ul><li>Usuário escolhe a opção de comprovantes</li><li>Usuário seleciona o período em que a operação foi realizada</li><li>Usuário escolhe a transação procurada.</li></ul> |
| **Restrição**| <ul><li>Usuário deve estar <a href="login">logado</a>.</li><li>Usuário deve possuir uma transação executada previamente.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C08: Recarga de Celular<a id="celular"></a>
| **Título**| Recarga de celular |
|--|--|
| **Objetivo**| <ul><li>Adicionar créditos à uma linha telefônica.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário deve estar <a href="login">logado</a>.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema.</li></ul> |
| <br>**Recursos**| <ul><li><a href="#cadastro">Conta no aplicativo</a></li><li>Linha telefônica Pré-paga.</li><li><a href="#saldo">Saldo</a> disponível na conta do aplicativo.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li>Usuário deve escolher a opção Recarga de Telefone</li><li>Usuário deve pressionar Digitar número com DDD.</li><li>Usuário deve inserir número da linha telefônica</li><li>Usuário deve confirmar o número da linha telefônica.</li><li>Usuário deve escolher a operadora da linha telefônica.</li><li>Usuário deve confirmar a opção de operadora.</li><li>Usuário deve escolher o valor a ser creditado.</li><li>Usuário deve confirmar a operação de recarga.</li></ul> |
| **Restrição**| <ul><li>Usuário deve estar <a href="login">logado</a>.</li><li>Usuário deve possuir <a href="#saldo">saldo</a> suficiente para a transação.</li></ul> |
| <br><br>**Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li><li>Preenchimento de dados incorreta.</li><li><a href="#saldo">Saldo</a> insuficiente.</li></ul> |

<!--
## Receber Seguro<a id="seguro"></a>
| **Título**| Receber Seguro |
|--|--|
| **Objetivo**| <ul><li></li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário deve estar <a href="login">logado</a>.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema.</li></ul> |
| <br><br>**Recursos**| <ul><li></li><li></li><li></li><li></li></ul> |
| <br><br><br>**Episódios**| <ul><li></li><li></li><li></li><li></li><li>U</li><li></li></ul> |
| **Restrição**| <ul><li></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |
-->


### C09: Consultar Saldo <a href="#saldo"></a>
| **Título**| Consultar <a href="#saldo">saldo</a> |
|--|--|
| **Objetivo**| <ul><li>Consultar saldo da conta</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| **Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Mostrar saldo”.</li></ul> |
| **Restrição**| <ul><li>O usuário deve possuir <a href="#cadastro">cadastro.</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C10: Realizar transferências<a id="transferencia"></a>
| **Título**| Realizar transferências |
|--|--|
| **Objetivo**| <ul><li>Transferir dinheiro para outra conta.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema</li><li>Outra Conta</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Transferir dinheiro”.</li><li>Selecionar como deseja transferir.</li><li>Inserir dados da conta para qual deseja transferir.</li><li>Digitar quanto deseja mandar.</li><li>Conferir os dados e valores.</li><li>Digitar senha do Caixa Tem.</li><li>Visualizar o comprovante.</li></ul> |
| **Restrição**| <ul><li>O usuário deve possuir <a href="#cadastro">cadastro.</a></li><li>O usuário deve possuir <a href="#saldo">dinheiro na conta</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li><li>Não inserir os dados corretos da outra conta.</li></ul> |

### C11: Fazer recarga de transporte<a id="transporte"></a>
| **Título**| Fazer recarga de transporte |
|--|--|
| **Objetivo**| <ul><li>Realizar recarga de transporte.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições: <ul><li>Possuir o app CaixaTem.</li><li>Possuir cartão de transporte.</li></ul></li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema</li><li>Cartão de transporte</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Recarga de transporte”.</li><li>Selecionar a Cidade/UF.</li><li>Escolher a empresa de transporte.</li><li>Inserir os dados e o valor que deseja recarregar.</li><li>Conferir se os dados estão corretos.</li><li>Digitar senha do Caixa Tem para concluir o processo.</li></ul> |
| **Restrição**| <ul><li>O usuário deve possuir <a href="#cadastro">cadastro.</a></li><li>O usuário deve possuir <a href="#saldo">dinheiro na conta</a>.</li><li>O usuário deve possuir um cartão de transporte.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C12: Contratar Seguro Apoio Família <a id="apoio"></a>
| **Título**| Contratar Seguro Apoio Família |
|--|--|
| **Objetivo**| <ul><li>Contratar seguro apoio família pelo Caixa Tem.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Seguro Apoio Família”.</li><li>Visualizar mensagens automáticas explicando como funciona o seguro.</li><li>Selecionar a opção “Quero Comprar”.</li></ul> |
| **Restrição**| <ul><li>O usuário deve possuir <a href="#cadastro">cadastro.</a></li><li>O usuário deve possuir <a href="#saldo">dinheiro suficiente</a> para contratar o seguro.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone sem bateria.</li></ul> |

### C13: Gerar código para pagar contas na lotérica<a id="loterica"></a>
| **Título**| Gerar código para pagar contas na lotérica |
|--|--|
| **Objetivo**| <ul><li>Gerar um código para o usuário pagar contas na lotérica sem cartão.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Pagar na Lotérica”.</li><li>O sistema irá gerar um código válido por 24 horas.</li></ul> |
| **Restrição**| <ul><li>O usuário deve possuir <a href="#cadastro">cadastro.</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone sem bateria.</li></ul> |

### C14: Utilizar cartão de débito virtual<a id="cartao"></a>
| **Título**| Utilizar cartão de débito virtual |
|--|--|
| **Objetivo**| <ul><li>Gerar um código de segurança para o usuário realizar compras na internet com o cartão de débito virtual.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Cartão de Débito Virtual”.</li><li>Visualizar dados do cartão de débito virtual.</li><li>Selecionar a opção de gerar código de segurança.</li><li>O sistema irá gerar um código de segurança válido para 1 compra.</li></ul> |
| **Restrição**| <ul><li>O usuário deve possuir <a href="#cadastro">cadastro.</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C15: Gerar código para saque sem cartão<a id="saque"></a>
| **Título**| Gerar código para saque sem cartão |
|--|--|
| **Objetivo**| <ul><li>Sacar dinheiro no caixa eletrônico com o código gerado.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Saque sem Cartão”.</li><li>Selecionar a opção “Gerar código para saque”.</li><li>Digitar senha do Caixa Tem.</li><li>O sistema irá gerar um código válido por 1 hora.</li></ul> |
| **Restrição**| <ul><li>O usuário deve possuir <a href="#cadastro">cadastro.</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C16: Realizar pagamentos com boleto<a id="boleto"></a>
| **Título**| Realizar pagamentos com boleto |
|--|--|
| **Objetivo**| <ul><li>Pagar uma conta pelo Caixa Tem.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Realizar pagamentos”.</li><li>Escolher forma de inserção de código de barras.</li><li>Inserir código de barras.</li><li>Conferir os dados do pagamento.</li><li>Selecionar a opção de realizar pagamento.</li><li>Digitar senha do Caixa Tem.</li><li>Salvar ou compartilhar comprovante de pagamento.</li></ul> |
| **Restrição**| <ul><li>O usuário deve possuir <a href="#cadastro">cadastro.</a></li><li>O usuário deve possuir o código de barras da conta.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li><li>Inserir o código de barras de forma incorreta.</li></ul> |

### C17: Realizar pagamentos com PIX<a id="pix"></a>
| **Título**| Realizar pagamentos com PIX |
|--|--|
| **Objetivo**| <ul><li>Pagar uma conta pelo Caixa Tem.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li>Usuário</li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “PIX”.</li><li>Selecionar a opção “Pagar”.</li><li>Escolher a chave Pix que será utilizada.</li><li>Inserir o valor da transferência.</li><li>Conferir os dados.</li><li>Digitar senha do Caixa Tem para concluir o processo.</li></ul> |
| **Restrição**| <ul><li>O usuário deve possuir <a href="#cadastro">cadastro.</a></li><li>O usuário deve possuir uma chave pix cadastrada.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

</center>

## 3. Bibliografia <a id="Bibliografia"></a>
<p align = "justify"> [1] FELICÍSSIMO, C. H.; LEITE, J. C. S. P.; BREITMAN, K. K; SILVA, L. F. C&L: <strong> Um
Ambiente para Edição e Visualização de Cenários e Léxicos.</strong> Rio de Janeiro. Disponível
<a href="http://pes.inf.puc-rio.br/cel/Artigos/C&L.pdf">aqui</a> .</p>

## Versionamento
<center>

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 26/08/2021 | Criação da página | Fernando Calil |
| 1.1 | 27/08/2021 | Adição da introdução | Lucas Gomes |
| 1.2 | 27/08/2021 | Adição dos primeiros Cenários | Fernando Calil |
| 1.3 | 28/08/2021 | Adição de Cenários | Lucas Gomes |
| <br>1.4 | <br>28/08/2021 | Adição de mais Cenários<br>Revisão de layout<br>Adição de links correspondentes |<br> Fernando Calil |
| 1.5 | 31/08/2021 | Melhorias no layout | Lucas Gomes |



</center>