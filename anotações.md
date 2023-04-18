Oracle + Alura - Treinamento 17/04/2023

Logica de Programação 1

Boa prática manter o uso da tag, nem todos os navegadores detectam o encoding automaticamente.
<meta charset="UTF-8">

tag Ancora, para criar links da web
<a href="link">texto</a>

JS é uma linguagem dinamica, linguagem de programação
tag <script>

pop-up na tela
<script>
alert("texto");
</script>

Concatenação

tag - aceita escrever um documento dentro do JS que vai aparecer no HTML

document.write()

Math.round - arredonda o resultado

Criar uma função
const pulaLinha = () => {};

function pulaLinha(){codigo};
pulaLinha();

prompt("");
função que retorna um valor, ele interaje com o usuario.

ex: prompt("qual sua altura");
o usuario responde, e ele captura a resposta do usuario.

= recebe
=== igualdade


ler numero = parseInt(prompt(""))

o prompt sempre le string, o parseInt é para ler numero

TAG HTML

<input> abre uma caixa de texto, entrada de dados

<button> botão

Como acessar o input no JS

var input = document.querySelector();

cria uma variavel para vc poder trabalhar com ela

o document.querySelector("nome da tag") que vai pegar esse dado para vc

.value = pegar o valor digitado

.onclick = quando clicar 

   input.value = "";  - vai zerar a caixa de texto
    input.focus(); - vai deixar a caixa de texto em evidencia para digitar novamente


<canvas></canvas> tela em branco no html 

Canvas  2d API - vc pode procurar a documentação para saber oq vc pode fazer 

