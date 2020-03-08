## Curso de JavaScript - Curso em Video

Repositorio criado para armazenar exercicios e anotações das aulas do curso de JavaScript do canal curso em video.


# Aula 06

Para transformar string em number podemos utilizar as seguintes notações:
  - Number.parseInt(string);
  - Number.parseFloat(string);
  - Number(string);

Já para transformar Numbers em string:
  - String(number);
  - number.toString();

Template Strings
São utilizados para poder criar uma string com variaveis

string = \`Esse é um template string ${variavel}\`

string.length -> Quantidade de caracteres
string.toUpperCase -> Todas as letras ficam em caixa alta
string.toLowerCase -> Todas as letras ficam em caixa baixa
string.toLocaleString('pt-BR', {style: 'currency', currency: 'EUR'}) -> formata a string para a localidade passada 

# Aula 07 

Operadores aritméticos

- number +  number -> Soma
- number -  number -> Subtração 
- number *  number -> Multiplicação
- number /  number -> Divisor
- number %  number -> Resto da divisão inteira
- number ** number -> Potencia

Os parênteses mudam a ordem de precedência.

# Aula 08

Operadores relacionais

- number >   number -> Maior
- number <   number -> Menor 
- number >=  number -> Maior igual
- number <=  number -> Menor igual
- number ==  number -> Igual
- number !=  number -> Diferente

Se adicionarmos mais um = adicionamos a validação de tipo.

por isso 5 == "5" retorna true
e 5 === "5" retorna false 

Operadores Lógicos

- !  -> Negação
- && -> Conjunção ou É lógico
- || -> Disjunção ou OU lógico

Operador ternário
 - teste ? true : false

  - ex : media >7 ? "Aprovado" : "Reprovado"

# Aula 09
O que é a DOM (Document Object Model)

Funciona como uma árvore hierárquica
E possível inserir código na pagina HTML com Js por meio do DOM adicionando novos nodes na árvore

existem as seguintes maneiras de selecionar nodes:
- por Marca  -> getElementsByTagName()
- por ID     -> getElementById()1
- por Nome   -> getElementsByName()
- por Classe -> getElementsByClassName()
- por Seletor-> querySelector()


innerText -> Texto interno da tag html
innerHtml -> pega todo HTML do node
