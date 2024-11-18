Análise e Desenvolvimento de Sistemas  
**Programação Frontend I**  
Prof. Adriano Lima  
**Aluno: Sofia Alves Toreti**

# **Projeto 1: Página Pessoal**

## Elementos de HTML e CSS usados  no desenvolvimento da página.

---
<br>

* # **HTML**

  1. ## **Slide 1: Introdução a HTML**

     1. ### Elementos estruturais do HTML

        - \<\!DOCTYPE html\>, \<html\>, \<head\> e \<body\>.

  2. ## **Slide 2: Semântica do HTML**

     1. ### Elementos semânticos

        - \<header\> : presente em todas as páginas.

        - \<nav\> : presente nas páginas main.html e portfolio.css.

        - \<section\> : presente em todas as páginas.

        - \<article\> : presente na página portfolio.html.

        - \<footer\> : presente nas páginas main.html e portfolio.css.

  3. ## **Slide 3: Validação no HTML**

     1. Utilizado em todas os documentos ao longo do desenvolvimento da página.

  4. ## **Slide 4: Elementos do HTML 1**

     1. ### Elementos Genéricos

        - \<div\> : utilizado diversas vezes ao longo do projeto.

     2. ### Elementos de Identificação

        - id=”” : usado principalmente para auxiliar a navegação do usuário na página por meio de hiperlinks.

        - class=”” : usado em quase todos os elementos das páginas para fácil acesso pelo CSS.

     3. ### Caracteres de Escape

        - Nenhuma caractere de escape foi utilizada no desenvolvimento da página.

     4. ### Links

        - Hiperlinks foram usados todos para o redirecionamento da navegação do usuário – tanto para navegação interna dos documentos existentes, quanto com URLs da internet.

     5. ### Imagens

        - Imagens foram usadas como botões e como ilustrações dos projetos disponíveis no portifólio.

        - Todas as imagens possuem título alternativo para acessibilidade.

  5. ## **Slide 5: Elementos do HTML 2**

     1. ### Tabelas

        - A tabela foi usada na página main.css, dentro da \<main\> para mostrar a grande de horários.

        - Além dos elementos-base da tabela, como \<table\>, \<tr\>, \<th\> e \<td\>, elementos de mescla de colunas/linhas colspan/rowspan, scope e \<tbody\> foram usados para compor a grade.

     2. ### Mídia Incorporada

        - Nenhuma mídia incorpora foi utilizada.

  6. ## **Slide 6: Elementos do HTML 3**

     1. ### Formulários

        - Formulário foi usado como forma de contato no \<footer\> – o usuário inseriria seu email e uma mensagem que seria enviada direto da página.

        - Elementos usados foram: \<forms\>, para agrupar os elementos, \<input type=”text”\>, \<input type=”email”\>, \<textarea\>.

        - Nenhum value=”” foi atribuido por falta de necessidade.

        - name=”” foi usado para linkar o \<input\> ao \<label\>.

        - Todos os elementos possuem um placeholder=””.
<br><br><br>
---
<br>

* # **CSS**

  1. ## **Slide 7: Introdução ao CSS**

     1. ### Inserindo ao Documento

        - Todas as folhas de estilo foram linkadas ao documento HTML através dos elementos \<link\> e @import url(); 

     2. ### Famílias de Fontes

        - O tipo de fonte escolhido foi a sem-serifa, pela sua modernidade e coerência com o objetivo do projeto.

        - A fonte principal escolhida foi a Helvetica.

  2. ## **Slide 8: Aplicação do CSS ao HTML**

     1. ### Dimensionamento

        - O dimensionamento de todas as páginas foram feitas conforme o formato box-sizing: border-box;

        - width, height, margin, padding e border foram utilizados em quase todos os elementos dos documentos html.

        - Opção de overflow não foi utilizado em nenhum momento.

     2. ### Cores 

        - Escolhidas em código hexadecimal.

     3. ### Seletores 

        - seletores individuais, por grupos e descendentes foram usados, dependendo da necessidade e especificidade do estilo usado.

        - Seletores de classe utilizados na grande maioria dos casos para seleção de estilos, em casos isolados foi utilizado o id.

        - footer.css, linha 77 e 81\.

        - projects.css, linha 45 e 78\.

  3. ## **Slide 9: Posicionamento de Elementos**

     1. ### Pseudo-classes

        - :hover : usado principalmente para animações e edição do ponteiro.

     2. ### Pseudo-elementos

        - ::placeholder : para estilização dos placeholders do contato encontrado no \<footer\>.

     3. ### Flexbox

        - usado em força nos links de navegação na \<header\> e \<footer\>.

        - posicionamento de \<p\> uma ao lado do outro.

        - posicionamento de \<div\> lado a lado.

  4. ## **Slide 10: Posicionamento**

     1. ### Position

        - Posição fixed usada na header.

        - Posição relative utilizada em botões de hiperlink na folha de estilo portfolio.css

     2. ### Grid

        - Utilizada na folha de estilo portfolio.css, na galeria de projetos, formando uma grade 3x2 de \<article\>.

  5. ## **Slide 11: Responsividade**

     1. ### Media query:

        - @media screen and (max-width: \---px) : utilizado para realizar a responsividade de todas as páginas, da maior resolução 2000px à menor 360px;

        - Foi criado folhas de estilo separadas para cada seção com o intuito de trabalhar com a responsividade de forma mais organizada.

     2. ### Comprimento de Linha

        - Houve a preocupação de deixar todas as linhas de texto entre 42 e 75 caracteres incluindo espaços.

     3. ### Deslocamento de Layout

        - Modificações necessárias foram feitas nos displays flexbox e grid.

     4. ### Menu de Navegação

        - Apesar de algumas tentativas, por limitações do projeto, a responsividade do menu resumiu-se em seu redimensionamento.

  6. ## **Slide 12: Avançando no CSS**

     1. ### Transições

        - Foram usadas em abundância no projeto.

        - Variações de 0,2s à 0,3s e 0,5s

        - Aplicados todos na pseudo-classe :hover.

     2. ### Transformações

        - scale() e translateY() foram usadas em conjunto em: h1, h2 e h3, hiperlinks, e seleção de projetos na main.html (projects.css) e projects.html (portfolio.css).

     3. ### Variáveis

        - Quase todas as cores da página foram definidas através de variáveis, salvo cores do form.

        - Variável para fonte também foi criada.

     4. ### Limpando Estilos

        - Nenhuma folha de estilo definida para “limpar” foi escolhida da web, ainda que o arquivo index.css foi utilizado para padronizar comportamento e cores gerais das outras páginas, como margens, paddings, cores e tamanhos.
<br><br><br>
---
