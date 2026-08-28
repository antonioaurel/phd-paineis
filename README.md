# Painéis — uso responsável de IA no ensino de TI

Retrato **estático e somente leitura** dos painéis da pesquisa de Doutorado
Profissional em Engenharia de Software (CESAR School).

👉 **https://antonioaurel.github.io/phd-paineis/**

| Painel | O que é |
|---|---|
| [Referencial teórico](referencial/) | Os artigos da base, com temas, eixos, procedência e a triagem de leitura |
| [Habilidades nas entrevistas](habilidades/) | O que 27 docentes apontaram, com nomes substituídos por `Docente NN` |

## O que estas páginas não são

**Não são resultado de revisão sistemática.** A base de artigos é coleta
oportunista, sem busca protocolada, e não sustenta alegação de cobertura. A
triagem é decisão de leitura da pessoa pesquisadora, não critério aplicado por
pipeline.

**Não gravam nada.** Os números refletem o momento em que a página foi gerada.
Os controles de marcação estão desativados de propósito: botão que aceita
clique e não guarda é pior que botão ausente.

## Privacidade

Os participantes aparecem como `Docente 01`..`Docente 27`. A aba de respostas
verbatim não faz parte desta versão.

Instituição e área foram mantidas por decisão da pessoa pesquisadora. Vale
dizer o que isso implica: em uma cidade, o par instituição + área restringe
bastante quem pode ser. O pseudônimo reduz a exposição, não a elimina.

Autores de artigos aparecem com o nome real — são autoria de trabalho
publicado, que é informação pública, e nada aqui diz quem foi entrevistado.

## Como é gerado

Este repositório é só a casca pública. A fonte, os dados e o histórico ficam
num repositório privado. As páginas são geradas por `tools/publica_pages.py`,
que congela os dados das rotas do servidor local dentro do HTML.
