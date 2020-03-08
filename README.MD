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

Operadores 