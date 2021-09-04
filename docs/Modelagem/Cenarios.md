# Cenários

## 1. Introdução

<p style="text-indent: 40px; align="justify"> Cenários são descrições de situações comuns ao cotidiano e que devem levar em conta os aspectos de usabilidade e permitir o aprofundamento do conhecimento do problema, a unificação de critérios, a obtenção do compromisso de clientes e/ou usuários, a organização de detalhes e o treinamento de pessoas.</p>
<p style="text-indent: 40px; align="justify">Cada cenário descreve, através de linguagem natural semi-estruturada, uma situação específica de uma aplicação de software, priorizando seu comportamento.<a href="#Bibliografia">[1]</a><br></p>

## 2. Cenários

<center>

### C01: Cadastro
| **Título**| Cadastro |
|--|--|
| **Objetivo**| <ul><li>Criar <a href="../Lexicos#Conta">conta</a> de <a href="../Lexicos#Usuario">usuário</a>.</li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela inicial da aplicação</li><li>Tempo - A qualquer momento.</li><li>Pré-condições:<ul><li>Ter aplicativo instalado.</li><li>Ter acesso a internet</li></ul></li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema.</li></ul> |
| <br><br><br>**Recursos**| <ul><li>Smartphone</li><li>Acesso a Internet</li><li>CPF</li><li>Email</li><li>Numero de telefone</li><li>CEP</li></ul> |
| <br><br><br><br><br><br><br><br>**Episódios**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> insere CPF.</li><li><a href="../Lexicos#Usuario">Usuário</a> Confirma ação.</li><li><a href="../Lexicos#Usuario">Usuário</a> escolhe opção de <a href="../Lexicos#Conta">cadastro.</a></li><li><a href="../Lexicos#Usuario">Usuário</a> insere CPF.</li><li><a href="../Lexicos#Usuario">Usuário</a> insere nome completo.</li><li><a href="../Lexicos#Usuario">Usuário</a> insere telefone.</li><li><a href="../Lexicos#Usuario">Usuário</a> confirma telefone</li><li><a href="../Lexicos#Usuario">Usuário</a> insere data de nascimento.</li><li><a href="../Lexicos#Usuario">Usuário</a> insere CEP</li><li><a href="../Lexicos#Usuario">Usuário</a> insere email.</li><li><a href="../Lexicos#Usuario">Usuário</a> confirma email</li><li><a href="../Lexicos#Usuario">Usuário</a> insere senha</li><li><a href="../Lexicos#Usuario">Usuário</a> confirma senha</li><li><a href="../Lexicos#Usuario">Usuário</a> marca o campo captcha.</li><li><a href="../Lexicos#Usuario">Usuário</a> finaliza <a href="../Lexicos#Conta">cadastro.</a></li></ul> |
| **Restrição**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> deve ter documentação válida.</li></ul> |
| <br><br>**Exceção**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> perde acesso a Internet.</li><li>Smartphone está sem bateria.</li><li><a href="../Lexicos#Usuario">Usuário</a> não informa os dados corretos.</li><li><a href="../Lexicos#Usuario">Usuário</a> não marca campo captcha.</li></ul> |

### C02: Login
| **Título**| Login |
|--|--|
| **Objetivo**| <ul><li>Autenticar o <a href="../Lexicos#Usuario">usuário</a> no sistema.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela inicial do aplicativo.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - <a href="../Lexicos#Usuario">Usuário</a> não pode estar <a href="../Lexicos#Login">Logado</a> do aplicativo.<br></li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a>.</li></ul> |
| **Recursos**| <ul><li><a href="../Lexicos#Conta">Conta no aplicativo</a></li></ul> |
| <br><br><br>**Episódios**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> abre o aplicativo.</li><li><a href="../Lexicos#Usuario">Usuário</a> insere CPF.</li><li><a href="../Lexicos#Usuario">Usuário</a> confirma ação.</li><li><a href="../Lexicos#Usuario">Usuário</a> insere CPF.</li><li><a href="../Lexicos#Usuario">Usuário</a> insere senha.</li><li><a href="../Lexicos#Usuario">Usuário</a> confirma ação.</li></ul> |
| **Restrição**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li></ul> |
| <br>**Exceção**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> perde acesso a Internet.</li><li>Smartphone está sem bateria.</li><li><a href="../Lexicos#Usuario">Usuário</a> não informa os dados corretos.</li></ul> |


### C03: Extrato
| **Título**| Extrato |
|--|--|
| **Objetivo**| <ul><li>Verificar as transações realizadas na <a href="../Lexicos#Conta">conta</a>.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - <a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema.</li></ul> |
| **Recursos**| <ul><li><a href="../Lexicos#Conta">Conta no aplicativo</a>.</li></ul> |
| **Episódios**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> seleciona a funcionalidade de <a href="../Lexicos#Extrato">extrato</a>.</li><li><a href="../Lexicos#Usuario">Usuário</a> seleciona o período desejado.</li></ul> |
| **Restrição**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li><li><a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |


### C04: Calendário do auxílio emergencial
| **Título**| Calendário do auxílio emergencial |
|--|--|
| **Objetivo**| <ul><li>Consultar calendário de liberação do auxílio emergencial.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - <a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema.</li></ul> |
| **Recursos**| <ul><li><a href="../Lexicos#Conta">Conta no aplicativo</a></li></ul> |
| **Episódios**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> seleciona a opção de <a href="../Lexicos#Transferir">transferência</a>.</li><li><a href="../Lexicos#Usuario">Usuário</a> escolhe a opção Ver calendário.</li></ul> |
| **Restrição**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li><li><a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C05: Informe de Rendimentos
| **Título**| Informe de Rendimentos |
|--|--|
| **Objetivo**| <ul><li>Consultar os <a href="../Lexicos#Rendimento">rendimentos</a> da <a href="../Lexicos#Conta">conta</a> pra declaração de imposto.</li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - <a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema.</li></ul> |
| **Recursos**| <ul><li><a href="../Lexicos#Conta">Conta no aplicativo</a>.</li></ul> |
| **Episódios**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> escole a opção Informe de <a href="../Lexicos#Rendimento">rendimentos</a>.</li><li><a href="../Lexicos#Usuario">Usuário</a> seleciona Ver informe de <a href="../Lexicos#Rendimento">rendimentos</a></li></ul> |
| **Restrição**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li><li><a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |


### C06: Consultar Programas Sociais
| **Título**| Consultar Programas Sociais |
|--|--|
| **Objetivo**| <ul><li>Consultar situação do programa social desejado.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - <a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema.</li></ul> |
| <br>**Recursos**| <ul><li><a href="../Lexicos#Conta">Conta no aplicativo</a>.</li><li>Elegibilidade para programa social.</li><li>NIS</li></ul> |
| **Episódios**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> escolhe o programa social desejado.</li></ul> |
| **Restrição**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li><li><a href="../Lexicos#Usuario">Usuário</a> deve ser elegível para o benefício social.</li></ul> |
| <br>**Exceção**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> não possui NIS.</li><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C07: Consultar Comprovantes
| **Título**| Consultar <a href="../Lexicos#Comprovante">Comprovantes</a> |
|--|--|
| **Objetivo**| <ul><li>Verificar comprovação de transações realizadas pela <a href="../Lexicos#Conta">conta</a>.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - <a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema.</li></ul> |
| **Recursos**| <ul><li><a href="../Lexicos#Conta">Conta no aplicativo</a></li></ul> |
| <br>**Episódios**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> escolhe a opção de <a href="../Lexicos#Comprovante">comprovantes</a></li><li><a href="../Lexicos#Usuario">Usuário</a> seleciona o período em que a operação foi realizada</li><li><a href="../Lexicos#Usuario">Usuário</a> escolhe a transação procurada.</li></ul> |
| **Restrição**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li><li><a href="../Lexicos#Usuario">Usuário</a> deve possuir uma transação executada previamente.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C08: Recarga de Celular
| **Título**| Recarga de celular |
|--|--|
| **Objetivo**| <ul><li>Adicionar créditos à uma linha telefônica.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - <a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema.</li></ul> |
| <br>**Recursos**| <ul><li><a href="../Lexicos#Conta">Conta no aplicativo</a></li><li>Linha telefônica Pré-paga.</li><li><a href="../Lexicos#Saldo">Saldo</a> disponível na <a href="../Lexicos#Conta">conta</a> do aplicativo.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> deve escolher a opção Recarga de Telefone</li><li><a href="../Lexicos#Usuario">Usuário</a> deve pressionar Digitar número com DDD.</li><li><a href="../Lexicos#Usuario">Usuário</a> deve inserir número da linha telefônica</li><li><a href="../Lexicos#Usuario">Usuário</a> deve confirmar o número da linha telefônica.</li><li><a href="../Lexicos#Usuario">Usuário</a> deve escolher a operadora da linha telefônica.</li><li><a href="../Lexicos#Usuario">Usuário</a> deve confirmar a opção de operadora.</li><li><a href="../Lexicos#Usuario">Usuário</a> deve escolher o valor a ser creditado.</li><li><a href="../Lexicos#Usuario">Usuário</a> deve confirmar a operação de recarga.</li></ul> |
| **Restrição**| <ul><li><a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="../Lexicos#login">logado</a>.</li><li><a href="../Lexicos#Usuario">Usuário</a> deve possuir <a href="../Lexicos#Saldo">saldo</a> suficiente para a transação.</li></ul> |
| <br><br>**Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li><li>Preenchimento de dados incorreta.</li><li><a href="../Lexicos#Saldo">Saldo</a> insuficiente.</li></ul> |

<!--
## Receber Seguro<a id="seguro"></a>
| **Título**| Receber Seguro |
|--|--|
| **Objetivo**| <ul><li></li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - <a href="../Lexicos#Usuario">Usuário</a> deve estar <a href="login">logado</a>.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema.</li></ul> |
| <br><br>**Recursos**| <ul><li></li><li></li><li></li><li></li></ul> |
| <br><br><br>**Episódios**| <ul><li></li><li></li><li></li><li></li><li>U</li><li></li></ul> |
| **Restrição**| <ul><li></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |
-->


### C09: Consultar Saldo
| **Título**| Consultar <a href="../Lexicos#Saldo">saldo</a> |
|--|--|
| **Objetivo**| <ul><li>Consultar <a href="../Lexicos#Saldo">saldo</a> da <a href="../Lexicos#Conta">conta</a></li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| **Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Mostrar <a href="../Lexicos#Saldo">saldo</a>”.</li></ul> |
| **Restrição**| <ul><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C10: Realizar transferências
| **Título**| Realizar transferências |
|--|--|
| **Objetivo**| <ul><li><a href="../Lexicos#Transferir">Transferir</a> dinheiro para outra <a href="../Lexicos#Conta">conta</a>.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema</li><li>Outra <a href="../Lexicos#Conta">Conta</a></li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “<a href="../Lexicos#Transferir">Transferir</a> dinheiro”.</li><li>Selecionar como deseja <a href="../Lexicos#Transferir">transferir</a>.</li><li>Inserir dados da <a href="../Lexicos#Conta">conta</a> para qual deseja <a href="../Lexicos#Transferir">transferir</a>.</li><li>Digitar quanto deseja mandar.</li><li>Conferir os dados e valores.</li><li>Digitar senha do Caixa Tem.</li><li>Visualizar o <a href="../Lexicos#Comprovante">comprovante</a>.</li></ul> |
| **Restrição**| <ul><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Saldo">saldo</a> na <a href="../Lexicos#Conta">conta</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li><li>Não inserir os dados corretos da outra <a href="../Lexicos#Conta">conta</a>.</li></ul> |

### C11: Fazer recarga de transporte
| **Título**| Fazer recarga de transporte |
|--|--|
| **Objetivo**| <ul><li>Realizar recarga de transporte.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições: <ul><li>Possuir o app CaixaTem.</li><li>Possuir cartão de transporte.</li></ul></li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema</li><li>Cartão de transporte</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Recarga de transporte”.</li><li>Selecionar a Cidade/UF.</li><li>Escolher a empresa de transporte.</li><li>Inserir os dados e o valor que deseja recarregar.</li><li>Conferir se os dados estão corretos.</li><li>Digitar senha do Caixa Tem para concluir o processo.</li></ul> |
| **Restrição**| <ul><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Saldo">saldo</a> na <a href="..Lexicos#Conta">conta</a></a>.</li><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir um cartão de transporte.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C12: Contratar Seguro Apoio Família
| **Título**| Contratar <a href="../Lexicos#Seguro">Seguro</a> Apoio Família |
|--|--|
| **Objetivo**| <ul><li>Contratar <a href="../Lexicos#Seguro">seguro</a> apoio família pelo Caixa Tem.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Seguro Apoio Família”.</li><li>Visualizar mensagens automáticas explicando como funciona o <a href="../Lexicos#Seguro">seguro</a>.</li><li>Selecionar a opção “Quero Comprar”.</li></ul> |
| **Restrição**| <ul><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Saldo">saldo</a> suficiente para contratar o <a href="../Lexicos#Seguro">seguro</a>.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone sem bateria.</li></ul> |

### C13: Gerar código para pagar contas na lotérica
| **Título**| Gerar código para pagar <a href="../Lexicos#Conta">conta</a>s na lotérica |
|--|--|
| **Objetivo**| <ul><li>Gerar um código para o <a href="../Lexicos#Usuario">usuário</a> pagar <a href="../Lexicos#Conta">conta</a>s na lotérica sem cartão.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Pagar na Lotérica”.</li><li>O sistema irá gerar um código válido por 24 horas.</li></ul> |
| **Restrição**| <ul><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone sem bateria.</li></ul> |

### C14: Utilizar cartão de débito virtual
| **Título**| Utilizar cartão de débito virtual |
|--|--|
| **Objetivo**| <ul><li>Gerar um código de segurança para o <a href="../Lexicos#Usuario">usuário</a> realizar compras na internet com o cartão de débito virtual.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Cartão de Débito Virtual”.</li><li>Visualizar dados do cartão de débito virtual.</li><li>Selecionar a opção de gerar código de segurança.</li><li>O sistema irá gerar um código de segurança válido para 1 compra.</li></ul> |
| **Restrição**| <ul><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C15: Gerar código para saque sem cartão
| **Título**| Gerar código para <a href="../Lexicos#Saque">saque</a> sem cartão |
|--|--|
| **Objetivo**| <ul><li>Sacar dinheiro no caixa eletrônico com o código gerado.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção <a href="../Lexicos#Saque">Saque</a> sem Cartão”.</li><li>Selecionar a opção “Gerar código para <a href="../Lexicos#Saque">saque</a>”.</li><li>Digitar senha do Caixa Tem.</li><li>O sistema irá gerar um código válido por 1 hora.</li></ul> |
| **Restrição**| <ul><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li></ul> |

### C16: Realizar pagamentos com boleto
| **Título**| Realizar pagamentos com boleto |
|--|--|
| **Objetivo**| <ul><li>Pagar uma <a href="../Lexicos#Conta">conta</a> pelo Caixa Tem.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “Realizar pagamentos”.</li><li>Escolher forma de inserção de código de barras.</li><li>Inserir código de barras.</li><li>Conferir os dados do pagamento.</li><li>Selecionar a opção de realizar pagamento.</li><li>Digitar senha do Caixa Tem.</li><li>Salvar ou compartilhar <a href="../Lexicos#Comprovante">comprovante</a> de pagamento.</li></ul> |
| **Restrição**| <ul><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir o código de barras da <a href="../Lexicos#Conta">conta</a>.</li></ul> |
| **Exceção**| <ul><li>Não ter acesso à internet.</li><li>Smartphone descarregado.</li><li>Inserir o código de barras de forma incorreta.</li></ul> |c

### C17: Realizar pagamentos com PIX
| **Título**| Realizar pagamentos com PIX |
|--|--|
| **Objetivo**| <ul><li>Pagar uma <a href="../Lexicos#Conta">conta</a> pelo Caixa Tem.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Possuir o app CaixaTem.</li></ul>|
| **Atores**| <ul><li><a href="../Lexicos#Usuario">Usuário</a></li><li>Sistema</li></ul> |
| **Recursos**| <ul><li>Acesso à internet.</li><li>Aplicativo instalado.</li></ul> |
| <br><br><br><br>**Episódios**| <ul><li>Abrir o aplicativo Caixa Tem.</li><li>Selecionar a opção “<a href="../Lexicos#PIX">PIX</a>”.</li><li>Selecionar a opção “Pagar”.</li><li>Escolher a chave <a href="../Lexicos#PIX">PIX</a> que será utilizada.</li><li>Inserir o valor da <a href="../Lexicos#Transferir">transferência</a>.</li><li>Conferir os dados.</li><li>Digitar senha do Caixa Tem para concluir o processo.</li></ul> |
| **Restrição**| <ul><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir <a href="../Lexicos#Conta">cadastro.</a></li><li>O <a href="../Lexicos#Usuario">usuário</a> deve possuir uma chave <a href="../Lexicos#PIX">PIX</a> cadastrada.</li></ul> |
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