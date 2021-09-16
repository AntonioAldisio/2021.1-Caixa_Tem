# Verificação do NFR Framework

## 1. Introdução
<p style="text-indent: 40px; align="justify">
O presente documento visa verificar o artefato do <a href = "/2021.1-Caixa_Tem/Modelagem/NFR_Framework/">NFR Framework</a>, afim de procurar quaisquer erros no modelo em termos de notação, processo ou procedimentos atraves da técnica de Inspeção. <a href="#Bibliografia">[1]</a></p>
</p>

## 2. Planejamento 
<p style="text-indent: 40px; align="justify">Foi utilizado um checklist para a realização da Inspeção:</p>

<center>

| ID| Tópico |
|:--:|:--:|
| 01 | Os Softgoals estão autoexplicativos? |
| 02 | Os Softgoals representam requisitos não funcionais? |
| 03 | Possui Propagação de Impacto? |
| 04 | Possui Softgoals de Afirmação? | 
| 05 | Contribuições foram aplicadas corretamente? |
| 06 | A direção das setas está correta? |
| 07 | Os Softgoals possuem rótulos? |
| 08 | A decomposição de Softgoals foi realizada corretamente? |
| 09 | As nuvens foram utilizadas corretamente? | 
| 10 | Existem contribuições negativas? | 
| 11 | Existem contribuições positivas? | 
| 12 | Existe algum operador que tenha dependência (AND/OR) para atender o Softgoal? | 
| 13 | A ortografia está correta? | 


</center>

## 3. Verificação

| ID| Tópico | NFR Geral (Usabilidade) | NFR Eficácia | NFR Eficiência | NFR Satisfação |
|:-:|--|:-:|:-:|:-:|:-:|
| 01 | Os Softgoals estão autoexplicativos? |(&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 02 | Os Softgoals representam requisitos não funcionais? |(&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 03 | Possui Propagação de Impacto? |(&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 04 | Possui Softgoals de Afirmação? | (&#10004) | (&#10006) | (&#10006) | (&#10006) | 
| 05 | Contribuições foram aplicadas corretamente? |(&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 06 | A direção das setas está correta? |(&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 07 | Os Softgoals possuem rótulos? |(&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 08 | A decomposição de Softgoals foi realizada corretamente? |(&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 09 | As nuvens foram utilizadas corretamente? | (&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 10 | Existem contribuições negativas? | (&#10006) | (&#10006) | (&#10006) | (&#10006) | 
| 11 | Existem contribuições positivas? | (&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 12 | Existe algum operador que tenha dependência (AND/OR) para atender o Softgoal? | (&#10004) | (&#10004) | (&#10004) | (&#10004) | 
| 13 | A ortografia está correta? | (&#10004) | (&#10006) | (&#10004) | (&#10006) | 

## 4. Conclusão
<p style="text-indent: 40px; align="justify">
Após a Inspeção, foi possível concluir que o artefato de NFR Framework está satisfatório e atende ao padrão esperado. Porém, alguns erros foram encontrados:
<ul>
    <li>Os NFRs de Eficácia e Satisfação possuem alguns erros de acentuação.</li>
    <li>A ausência de mais Softgoals de Afirmação.</li>
    <li>A falta de contribuições negativas entre os Softgoals.</li>
</ul>
A partir dos pontos levantados, a equipe poderá aprimorar o artefato.
</p>

## 5. Bibliografia <a id="Bibliografia"></a>
<p align = "justify"> [1] SERRANO, Maurício; SERRANO, Milene. <strong>Requisitos - Aula 23</strong>. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.</p>
<p align = "justify"> [2] DA SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019. Dissertação (Mestrado em Ciência da Computação) - Universidade Federal de Pernambuco, Recife, 2019.</p>


## Versionamento
<center>

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 13/09/2021 | Criação da página | Antônio Aldisio |
| 2.0 | 15/09/2021 | Adição da verificação do NFR Framework | Antônio Aldisio |

</center>