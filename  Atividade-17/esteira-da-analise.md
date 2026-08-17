# Esteira da Análise — BiblioTech

**Estudante:** RENAN SOARES DA SILVA

## Funcionalidade 1: reservar livro

- **1.1 Fala do cliente:** "Quero ter o poder de reservar o livro para que quando esteja disponivel eu possa empresta-lo"
- **1.2 História de usuário:** Como Leitor , quero reservar um livro, para quando estiver disponivel poder pega-lo.
- **1.3 Requisito:** RF01 — O sistema deve permitir reservar livros.
- **1.4 Caso de uso (RF01):** Ator leitor → "Emprestar Livro".

## Funcionalidade 2: cadastrar novo livro 

- **2.1 Fala do cliente:** "tenho que ter uma maneirar de adicionar novos livros a biblioeca para atulizar o acervo de livros"
- **2.2 História de usuário:** Como Bibliotecario, quero cadastrar novos livros, para atualizar o acervo.
- **2.3 Requisito:** RF02 — O sistema deve permitir o cadastro de novos livros.
- **2.4 Caso de uso (RF02):** Ator Bibliotecario → "Cadastrar livro".

## Rastreabilidade

| Elipse no diagrama | Veio do requisito | Que veio da fala |
|---|---|---|
| Emprestar livro | RF01 | 1.1 |
| Cadastrar livro | RF02 | 2.1 |
|---|---|---|

## Caminho completo
|Fala do cliente| Historia de Usuario | RF | caso de uso |
|---|---|---|---|
|1.1|1.2|1.3|1.4|
|2.1|2.2|2.3|2.4|

<!-- Nível A: conte o caminho completo de cada funcionalidade,
     da fala do cliente até o que está desenhado no diagrama. -->

## Relacionamento entre casos de uso (nível A)

- Tipo: «include» 
- Entre: Emprestar livro e Consultar acervo
- Por que é esse e não o outro: Para emprestar um livro, primeiro tem que saber se ele está ou não no acervo.

## Autoavaliação

**Conceito pretendido:** A

- Conversei sobre esta atividade com: ninguém
- Esteira da análise: ## Caminho completo (Linha 27)
- Diagrama e notação: [Atividade-17/Bibliotech.drawio.png]( Atividade-17/Bibliotech.drawio.png)
- Rastreabilidade: ## Rastreabilidade (linha 19)
- Organização da entrega: ...