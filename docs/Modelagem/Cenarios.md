# Cenários

<<<<<<< Updated upstream
## 1. Introdução
=======
## 1


| **Título**| Cadastro |
|--|--|
| **Objetivo**| <ul><li>Criar conta de usuário.</li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela inicial da aplicação</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Ter aplicativo instalado.<br></li> &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp;Ter acesso a internet.</ul>|
| **Atores**| <ul><li>Usuário</li></ul> |
| <br><br><br>**Recursos**| <ul><li>Smartphone</li><li>Acesso a Internet</li><li>CPF</li><li>Email</li><li>Numero de telefone</li><li>CEP</li></ul> |
| <br><br><br><br><br><br><br><br>**Episódios**| <ul><li>Usuário insere CPF.</li><li>Usuário Confirma ação.</li><li>Usuário escolhe opção de cadastro.</li><li>Usuário insere CPF.</li><li>Usuário insere nome completo</li><li>Usuário insere telefone.</li><li>Usuário confirma telefone</li><li>Usuário insere data de nascimento.</li><li>Usuário insere CEP</li><li>Usuário insere email.</li><li>Usuário confirma email</li><li>Usuário insere senha</li><li>Usuário confirma senha</li><li>Usuário marca o campo captcha.</li><li>Usuário finaliza cadastro.</li></ul> |
| **Restrição**| <ul><li>Usuário deve ter documentação válida.</li></ul> |
| <br><br>**Exceção**| <ul><li>Usuário perde acesso a Internet.</li><li>Smartphone está sem bateria.</li><li>Usuário não informa os dados corretos.</li><li>Usuário insere algum dado incorreto.</li><li>Usuário não marca campo captcha.</li></ul> |


| **Título**| Login |
|--|--|
| **Objetivo**| <ul><li>Autenticar o usuário no sistema.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela inicial do aplicativo.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário não pode estar Logado do aplicativo.<br></li></ul>|
| **Atores**| <ul><li>Usuário.</li></ul> |
| **Recursos**| <ul><li>Conta no aplicativo</li></ul> |
| <br><br><br>**Episódios**| <ul><li>Usuário abre o aplicativo.</li><li>Usuário insere CPF.</li><li>Usuário confirma ação.</li><li>Usuário insere CPF.</li><li>Usuário insere senha.</li><li>Usuário confirma ação.</li></ul> |
| **Restrição**| <ul><li>Usuário deve possuir cadastro.</li></ul> |
| <br>**Exceção**| <ul><li>Usuário perde acesso a Internet.</li><li>Smartphone está sem bateria.</li><li>Usuário não informa os dados corretos.</li></ul> |



| **Título**| Extrato |
|--|--|
| **Objetivo**| <ul><li>Verificar as transações realizadas na conta.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades.</li><li>Tempo - A qualquer momento.</li><li>Pré-condições - Usuário deve estar logado.</li></ul>|
| **Atores**| <ul><li>Usuário</li></ul> |
| **Recursos**| <ul><li>Conta no aplicativo.</li></ul> |
| **Episódios**| <ul><li>Usuário seleciona a funcionalidade de extrato.</li><li>Usuário seleciona o período desejado.</li></ul> |
| **Restrição**| <ul><li>Usuário deve possuir cadastro.</li></ul> |
| **Exceção**| <ul></ul> |



| **Título**| Calendário do auxílio emergencial |
|--|--|
| **Objetivo**| <ul><li>Consultar calendário de liberação do auxílio emergencial.</li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Usuário deve estar logado.</li></ul>|
| **Atores**| <ul><li>Usuário</li></ul> |
| **Recursos**| <ul><li>Conta no aplicativo</li></ul> |
| **Episódios**| <ul><li>Usuário seleciona a opção de transferência.</li><li>Usuário escolhe a opção Ver calendário.</li></ul> |
| **Restrição**| <ul>Usuário deve possuir cadastro.</ul> |
| **Exceção**| <ul></ul> |

| **Título**| Informe de Rendimentos |
|--|--|
| **Objetivo**| <ul><li>Consultar o rendimentos da conta pra declaração de imposto.</li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Usuário deve estar logado.</li></ul>|
| **Atores**| <ul><li>Usuário</li></ul> |
| **Recursos**| <ul><li>Conta no aplicativo.</li></ul> |
| **Episódios**| <ul><li>Usuário escole a opção Informe de Rendimentos.</li><li>Usuário seleciona Ver informe de Rendimentos</li></ul> |
| **Restrição**| <ul><li>Usuário deve possuir cadastro.</li></ul> |
| **Exceção**| <ul></ul> |

| **Título**| Consultar Programas Sociais |
|--|--|
| **Objetivo**| <ul><li>Consultar situação do programa social desejado.</li></ul> |
| <br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Usuário deve estar logado.</li></ul>|
| **Atores**| <ul><li>Usuário</li></ul> |
| <br>**Recursos**| <ul><li>Conta no aplicativo.</li><li>Elegibilidade para programa social.</li><li>NIS</li></ul> |
| **Episódios**| <ul><li>Usuário escolhe o programa social desejado.</li></ul> |
| **Restrição**| <ul><li>Usuário deve ser elegível para o benefício social.</li></ul> |
| **Exceção**| <ul><li>Usuário não possui NIS.</li></ul> |

<!--
| **Título**|  |
|--|--|
| **Objetivo**| <ul><li></li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Usuário deve estar logado.</li></ul>|
| **Atores**| <ul><li>Usuário</li></ul> |
| <br><br>**Recursos**| <ul><li></li><li></li><li></li><li></li></ul> |
| <br><br><br>**Episódios**| <ul><li></li><li></li><li></li><li></li><li>U</li><li></li></ul> |
| **Restrição**| <ul><li></li></ul> |
| **Exceção**| <ul><li></li><li></li><li></li></ul> |

| **Título**|  |
|--|--|
| **Objetivo**| <ul><li></li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Usuário deve estar logado.</li></ul>|
| **Atores**| <ul><li>Usuário</li></ul> |
| <br><br>**Recursos**| <ul><li></li><li></li><li></li><li></li></ul> |
| <br><br><br>**Episódios**| <ul><li></li><li></li><li></li><li></li><li>U</li><li></li></ul> |
| **Restrição**| <ul><li></li></ul> |
| **Exceção**| <ul><li></li><li></li><li></li></ul> |

| **Título**|  |
|--|--|
| **Objetivo**| <ul><li></li></ul> |
| <br><br>**Contexto**|<ul><li>Local - Tela de lista de funcionalidades</li><li>Tempo - A qualquer momento</li><li>Pré-condições - Usuário deve estar logado.</li></ul>|
| **Atores**| <ul><li>Usuário</li></ul> |
| <br><br>**Recursos**| <ul><li></li><li></li><li></li><li></li></ul> |
| <br><br><br>**Episódios**| <ul><li></li><li></li><li></li><li></li><li>U</li><li></li></ul> |
| **Restrição**| <ul><li></li></ul> |
| **Exceção**| <ul><li></li><li></li><li></li></ul> |

-->

>>>>>>> Stashed changes

<p style="text-indent: 40px; align="justify"> Cenários são descrições de situações comuns ao cotidiano e que devem levar em conta os aspectos de usabilidade e permitir o aprofundamento do conhecimento do problema, a unificação de critérios, a obtenção do compromisso de clientes e/ou usuários, a organização de detalhes e o treinamento de pessoas.</p>
<p style="text-indent: 40px; align="justify">Cada cenário descreve, através de linguagem natural semi-estruturada, uma situação específica de uma aplicação de software, priorizando seu comportamento.<a href="#Bibliografia">[1]</a><br></p>

## Bibliografia <a id="Bibliografia"></a>
<p align = "justify"> [1] FELICÍSSIMO, C. H.; LEITE, J. C. S. P.; BREITMAN, K. K; SILVA, L. F. C&L: <strong> Um
Ambiente para Edição e Visualização de Cenários e Léxicos.</strong> Rio de Janeiro. Disponível
<a href="http://pes.inf.puc-rio.br/cel/Artigos/C&L.pdf">aqui</a> .</p>

## Versionamento
<center>

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 01/08/2021 | Criação da página | Fernando Calil |
| 1.1 | 27/08/2021 | Adição da introdução | Lucas Gomes |
| 1.2 | 27/08/2021 | Adição dos primeiros Cenários | Fernando Calil |


</center>