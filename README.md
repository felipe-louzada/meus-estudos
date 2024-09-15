# Meu Estudo

**Resumo JavaScript**

- A notação de colchetes é usada para acessar caracteres em uma string, começando pelo índice 0. Por exemplo, em `const firstName = "Charles"`, o primeiro caractere é acessado com `firstName[0]`. O valor será `"C"`. Para encontrar o primeiro caractere de qualquer string, use a sintaxe `[0]` após o nome da variável.


- Imutabilidade de Strings em JavaScript: Strings são imutáveis, o que significa que não é possível alterar diretamente seus caracteres. A única forma de modificar uma string é reatribuindo a variável a um novo valor.


- Acessando Caracteres Específicos em Strings com Notação de Colchetes: A notação de colchetes permite acessar caracteres específicos em uma string. A contagem começa do índice 0, sendo que o primeiro caractere de uma string é acessado com `[0]`, o segundo com `[1]`, e assim por diante.


- Obtendo o Último Caractere de uma String com Notação de Colchetes: Para acessar o último caractere de uma string, utiliza-se a expressão `[string.length - 1]`. Isso funciona porque `length` retorna o número total de caracteres na string, e como a indexação começa em 0, o último caractere está na posição `length - 1`.


- Acessando o N-ésimo Caractere a Partir do Fim de uma String: Para acessar o N-ésimo caractere a partir do fim de uma string, usamos a expressão `[string.length - N]`, onde `N` é a posição do caractere a partir do final. Isso permite acessar qualquer caractere contando de trás para frente na string.


- Peenchendo Espaços em Branco em Frases: Para completar uma frase com palavras fornecidas e suas próprias palavras, use a concatenação de strings com o operador `+`. Inclua espaços apropriados entre as palavras para formar uma frase completa e coerente. Utilize as variáveis fornecidas para substituir os espaços em branco na frase.


- Armazenando Valores Múltiplos em Arrays: Arrays permitem armazenar diversos tipos de dados em uma única variável. A criação de um array é feita usando colchetes e separando os itens com vírgulas. Um array pode conter diferentes tipos de dados, como strings e números, em uma única estrutura.


- Criando Arrays Aninhados: Arrays em JavaScript podem conter outros arrays, formando uma estrutura multidimensional. Por exemplo, o array: `const teams = [["Felipe", 20], ["Julia", 18]];` contém dois arrays internos, cada um representando nome e a idade. Para criar um array aninhado, você coloca arrays dentro de colchetes de outros arrays.


- Acessando Dados em Arrays com Índices: Você pode acessar elementos em um array usando índices, que são especificados dentro de colchetes. Arrays utilizam indexação baseada em zero, então o primeiro elemento tem o índice 0. Por exemplo:  

     `const array = [50, 60, 70];` 
     `console.log(array[0]); // Imprime 50` 
     `const data = array[1]; // data tem o valor 60`
     Para acessar o primeiro valor de um array, use o índice `0`.
     

-  Modificando Dados em Arrays com Índices: Diferente das strings, os dados dentro de arrays podem ser alterados diretamente. Mesmo que o array seja declarado com `const`, você pode modificar seus elementos. Por exemplo:
    `const ourArray = [50, 40, 30];`
    `ourArray[0] = 15; // Agora ourArray é [15, 40, 30]`


- Acessando Arrays Multidimensionais com Índices: Arrays multidimensionais são arrays dentro de arrays. Para acessar um elemento específico, use colchetes para cada nível de profundidade:
    `const arr = [`
      `[1, 2, 3],`
      `[4, 5, 6],`
      `[7, 8, 9],`
      `[[10, 11, 12], 13, 14]`
    `];`
    `const element = arr[2][1]; // Elemento 8`
    
- Adicionando Itens ao Final de um Array com `push`: O método `push()` permite adicionar um ou mais itens ao final de um array e retorna o novo comprimento do array. Por exemplo:
    `const fruits = ["apple", "banana", "cherry"];`
    `fruits.push("date", "elderberry");`
    `console.log(fruits); // ["apple", "banana", "cherry", "date", "elderberry"]`


- O método `push()` permite adicionar novos itens ao final de um array e retorna o novo comprimento do array. Use-o para estender arrays com novos elementos, mantendo a ordem de inserção.
    `const fruits = ["apple", "banana"];`
    `fruits.push("cherry", "date");`
    `console.log(fruits); // ["apple", "banana", "cherry", "date"]`


- O método `pop()` remove o último elemento de um array e retorna esse valor. Ele modifica o array original ao retirar o item final.
    `const numbers = [10, 20, 30];`
    `const removed = numbers.pop();`
    `console.log(removed); // 30`
    console.log(numbers); // [10, 20]


- O método .`pop()` remove o último elemento de um array e retorna esse valor. Ele modifica o array original ao retirar o item final, o `.shift( )` é igual ao `.pop` mas invés de remover o ultimo, remove o primeiro.
    `const numbers = [10, 20, 30];`
    `const removed = numbers.pop();`
    `console.log(removed); // 30`
    `console.log(numbers); // [10, 20]`
