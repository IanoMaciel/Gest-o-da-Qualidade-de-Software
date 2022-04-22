## Histórico de Versões

| Data       | Versão | Descrição            |         Autor             |
|:----------:|:------:|:--------------------:|:-------------------------:|
| 10/09/2021 | 0.1 | Criação do Documento com tema, épico, funcionalidades e user story  | @GeiseSaunier |
| 11/09/2021 | 0.2 | Revisão dos termos utilizados  | @GeiseSaunier e @IanoMaciel|
| 21/09/2021 | 0.3 | Revisão do backlog do produto  | @GeiseSaunier e @IanoMaciel|



# Versão 1

## Tema

| ID | DESCRIÇÃO |
|----|-----------|
|TM01| Autista |
|TM02| Profissional - Especialista |


## Épicos
| ID | DESCRIÇÃO | ID RELACIONADO (TEMA) |
|----|-----------|----------------|
| EP01 | Como um usuário autista, eu desejo encontrar o especialista mais perto de minha localidade | TM01 |
| EP02 | Como um usuário profissional, eu desejo receber uma notificação do paciente autista mais próximo, com nome e número de contato, para que eu possa entrar em contato em um horário mais adequado a minha agenda diária  | TM02 |

## Funcionalidades (Features)
| ID | DESCRIÇÃO | ID RELACIONADO (ÉPICOS) |
|----|-----------|----------------|
| FT01 | CRUD do usuário autista | EP01 |
| FT02 | CRUD do usuário especialista | EP02 |
| FT03 | Usuário autista deve localizar o profissional mais próximo| EP01 |
| FT04 | Usuário autista deve enviar notificação ao profissional mais próximo | EP01 e EP02|
| FT05 | Usuário especialista deve aceitar ou recusar a notificação do usuário autista | EP01 e EP02 |

## User Story

|    ID   |      Tipo     |     Eu como    |      Desejo       | De modo que | Prioridade | Status    | ID RELACIONADO (FEATURES) |
|:-------:|:-------------:|:--------------:|:-----------------:|:-----------:|:----------:|:---------:|:-------------------------------:|
|    US01    |   Funcional   | Usuário autista       | realizar meu cadastro no aplicativo autizando | eu consiga acessar meu perfil específico | Alta | Desenvolvimento | FT01 |
|    US01    |   Funcional   | Usuário profissional   | realizar meu cadastro no aplicativo autizando| eu consiga acessar meu perfil específico | Alta | Desenvolvimento | FT02 |
|    US01    |   Funcional   | Usuário autista       | encontrar um profissional/especialista mais próximo de mim | eu consiga enviar uma notificação com meu nome e número de contato para que o profissional entre em contato comigo | Alta | Desenvolvimento | FT03 |
|    US01    |   Funcional   | Usuário profissional       | receber notificação do usuário autista mais próximo | eu posso aceitar a notificação e consiga entrar em contato para atendê-lo, por um valor social, no horário mais adequado, de acordo com a minha agenda diária   | Alta | Desenvolvimento | FT04 |
