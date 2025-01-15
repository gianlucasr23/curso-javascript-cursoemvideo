# Curso de Javascript Curso em vídeo (Gustavo Guanabara)
Este repositório contem exercícios e projetos realizados durante o curso citado.

## Estrutura 
**EX001** Iniciando aprendizado : 

Uma página simples para iniciar com Javascript, HTML e css. Exibe uma mensagem de alerta (Alert), pergunta ao usuário se está gostando de Javascript (confirm), solicita o nome do usuário via campo de texto (prompt).

**EX002** Introdução input : 

Básico do desenvolvimento web com uma página simples e interação com usuário. Criamos uma página, aplicamos estilos css e utilizamos prompt no Javascript para interação com usuário.

**EX003** Soma de dois números : 

Aqui aprofundamos na interação com usuário usando javascript, e também tivemos a introdução a manipulação de variáveis e calculos simples.
* Criamos um programa que: 
- Solicita ao usuário dois números por meio de prompts.
- Converte as entradas de texto para números utilizando Number().
- Soma dois números e armazena o resultado em uma variável S.
- Exibe o resultado da soma em um alerta (window.alert) com template strings para mostrar os números e os resultados.

Aprendizados: 
- Conversão de entradas de texto para números em JS;
- Manipulação de variáveis;
- Uso de template strings para formatar saída de daos.

**EX004** Manipulação de Strings :

  Aqui utilizamos Javascript para capturar o nome do usuário e realizar manipulações básicas de texto.
- Solicitamos o nome do usuário;
- Exibimos o número de letras do nome do usuário utilizando nome.lenght;
- convertemos e exibimos em maiúsculas com nome.toLocaleUpperCase();
- convertemos e exibimos em minúscular com nome.ToLocaleLowerCase().

**EX005** Primeiros passos DOM : 

Introdução a DOM (Document object Model) Com javascript, mostrando como acessar e modificar elementos HTML dinamicamente.
- Em HTML, incluímos um título, dois parágrafos e uma div com id msg que contém o texto "Clique em mim"

* Acessando elementos DOM
- A variável corpo acessa o elemento `<body>` da página
- a variável p1 pega o segundo parágrafo `<p>` usando getElementBytagname
- A variável d acessa a div com o id msg usando querySelector.
- Acessa o elemento `<body>` e o segundo parágrafo da página.
- Seleciona a `div` com o id `msg` e altera a cor do seu texto para azul.

**EX006** Eventos DOM :

 Este exercício explora eventos do DOM, permitindo que o usuário interaja com elementos da página por meio de cliques e movimentos do mouse. 

- Em HTML, Criada uma div com id area, que possui um fundo verde (rgb(42, 139, 42)) e texto branco.
- A div tem um tamanho fixo (200px por 200px) e usa flexbox para centralizar o texto, tanto vertical quanto horizontalmente.

- O evento click altera o texto da div para "Clicou!" e a cor de fundo para vermelho.
- O evento mouseenter muda o texto para "Entrou" quando o mouse entra na área da div.
- O evento mouseout altera o texto para "Saiu" e o fundo volta a ser verde quando o mouse sai da área.
- Esses eventos são gerenciados através do addEventListener.

- Ao clicar na área, o texto muda para "Clicou!" e a cor de fundo para vermelho.
- Ao passar o mouse por cima, o texto muda para "Entrou!".
- Ao tirar o mouse da área, o texto retorna para "Saiu" e a cor de fundo volta a ser verde.

Aprendizado:
- Manipulação de eventos com `addEventListener`.
- Respostas a interações do usuário com `click`, `mouseenter` e `mouseout`.
- Estilização e manipulação de elementos HTML com JavaScript.


**EX007** Somando números: 

Permite o usuário somar dois números inseridos em campos de input e exibir o resultado na página.

- Em HTML, a página possuí dois campos de entrada (inpu), onde o usuário pode digitar números, um botão que ao ser clicado, chama a função Javascript para somar os números. A página exibe o resultado da soma dentro de uma div com o id res.

- A função somar() é acionada ao clicar no botão
- A função obtém os valores dos inputs de número, converte-os para Number, e realiza a soma. 
- O resultado da soma é exibido dinamicamente dentro da div#res

Aprendizado: 
- Manipulação de elementos de formulário, como `input` de tipo `Number`
- Conversão de valores como `Number()`
- Exibição de resultados na página com `InnerHTML`.
- Ação de eventos com botão de clique.


**EX008** Condicionais: 

Este exercício utiliza a estrutura condicional `if` para verificar se a velocidade do carro ultrapassa o limite de 70 km/h e exibe uma mensagem de multa caso isso aconteça.

- Verifica se a velocidade do carro excede o limite de 70 km/h.
- se a velocidade for maior que 70km/h, exibe a mensagem "você ultrapassou a velocidade permitida, MULTADO".
- independente da condição, exibe a mensagem "Dirija sempre com cuidado!"

Aprendizado: 
- Uso da estrutura condicional `if` para testar condições.
- Exibição de mensagens dinâmicas com `console.log`.

**EX009** Condionais parte 2:

- Este exercício usa uma estrutura condicional `if-else` para verificar se o usuário é brasileiro ou estrangeiro, com base no país informado. 

- Verifica se o valor da variável `país` é 'Brasil'.
- Se o país for diferente de 'Brasil', exibe a mensagem "Você é Estrangeiro!".
- Caso contrário, exibe "Você é Brasileiro!".

Aprendizado:

- Uso da estrutura condicional `if-else` para verificar diferentes condições.
- Exibição de mensagens baseadas no valor de uma variável.

**EX010**   Sistema de multas:

- Este exercício simula um sistema de verificação de velocidade, alertando o usuário se ele exceder o limite de 70 km/h.

- o usuário insere a velocidade do carro e, ao clicar no botão "verificar", o sistema mostra se a velocidade está acima de 70km/h.

- se a velocidade for maior que 70km/h, o usuário recebe a mensagem multa.
- se a velocidade for menor ou igual a 70km/h o sistema exibe um alerta para dirigir com cuidado.

Aprendizado:
- Manipulação de inputs numéricos (`input type="number"`).
- Uso de `querySelector` para capturar elementos.
- Manipulação de strings para exibir o resultado no HTML.