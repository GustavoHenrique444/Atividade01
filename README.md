# Atividade01
Atividade sobre os tipos de dados do java 

_Tipos de dados do java_ 
```
1- Byte
2- short 
3- Int
4- Long 
5- Boolean
6- char
7- float
8- double 
9- Null 
10- Number
11- Bigint 
12- String
13- Symbol
```
_Para que servem ?_
```
Byte- Armazena valores de 0 a 255.

short- Contém inteiros de 16 bits, que variam de -32.768 a 32.767, e também pode ser usado para economizar memória.

int- Um tipo de dado inteiro primario do SQL Server. 

Long- Contém inteiros de 64 bits, que variam de 9.223.372.036.854.775.808 a 9.223.372.036.854.775.807. 

Boolean- Representa uma entidade lógica que podem ter dois valores: true (verdadeiro) e false (falso).

Char- tipos de dados de caractere que sejam de tamanho fixo.

Float- O tipo de dado float serve para para guardar números de pontos flutuante.

Double- fornece as maiores e menores magnitudes possíveis para um número.

Null- o null é usado quando uma informação a ser cadastrada é desconhecida ou não aplicável.

Number- Representa um número que pode variar de 1 a 38 posições e a escala entre -84 a 127 posições, para valores inteiros o valor deve ser 0.

Bigint- É um tipo de dado múmerico que representa números interiros no formato de precisão arbitaria.  

String- É uma cadeia de caracteres alfonuméricos (Letras, Números e caracteres especiais). 

Symbol- Serve de identificador único 
```
_Exemplos do dados_
```
Byte- Um exemplo de dados de byte é: 01100110. Este é um número binário de 8 bits, ou seja, possui 8 dígitos binários que podem assumir o valor 0 ou 1. Esses dados de byte podem ser convertidos em decimal, hexadecimal ou octal, dependendo do contexto em que são usados. Os bytes de dados são frequentemente usados na programação para representar informações em formato binário, como imagens, arquivos, protocolos de rede, etc.

Short- Um exemplo de dado short em programação é: 32767. O short é um tipo de dado numérico inteiro de 16 bits, o que significa que ele pode armazenar valores inteiros dentro do intervalo de -32.768 a 32.767. Neste exemplo, 32767 é o maior valor que pode ser armazenado em um dado short sem sinal, ou seja, um short que não permite valores negativos. Em programação, dados short são utilizados quando é necessário armazenar números inteiros em um espaço de memória reduzido, com o objetivo de otimizar o desempenho do programa ou reduzir o consumo de memória.0

Int- Um exemplo de dado int em programação é: -2147483648. O int é um tipo de dado numérico inteiro de 32 bits, o que significa que ele pode armazenar valores inteiros dentro do intervalo de -2.147.483.648 a 2.147.483.647. Neste exemplo, -2147483648 é o menor valor que pode ser armazenado em um dado int com sinal. Em programação, dados int são utilizados para armazenar números inteiros que não exigem alta precisão, ocupando um espaço de memória maior do que os dados short, mas menor do que os dados long. Dados int são muito comuns em programação, sendo utilizados para realizar cálculos matemáticos, índices de arrays, entre outras aplicações.

long- Um exemplo de dado long em programação é: 9223372036854775807. O long é um tipo de dado numérico inteiro de 64 bits, o que significa que ele pode armazenar valores inteiros dentro do intervalo de -9.223.372.036.854.775.808 a 9.223.372.036.854.775.807. Neste exemplo, 9223372036854775807 é o maior valor que pode ser armazenado em um dado long com sinal. Em programação, dados long são utilizados para armazenar números inteiros que exigem alta precisão e/ou valores muito grandes, ocupando um espaço de memória maior do que os dados int e short. Dados long são comuns em programação científica e de engenharia, onde cálculos com números muito grandes ou muito pequenos são necessários.

Double- Um exemplo de dado double em programação é: 3.141592653589793. O double é um tipo de dado numérico de ponto flutuante de 64 bits, o que significa que ele pode armazenar valores numéricos decimais com alta precisão e com uma ampla faixa de valores. Em programação, dados double são comuns quando é necessário realizar cálculos matemáticos com números decimais e/ou quando é necessário armazenar números com muitas casas decimais. Dados double são mais precisos do que os dados float, que são de 32 bits, mas ocupam mais espaço em memória. Alguns exemplos de uso de dados double em programação incluem cálculos matemáticos em jogos, simulações físicas e financeiras. 

Char- Um exemplo de dado char em programação é: 'a'. O char é um tipo de dado que representa um caractere alfanumérico de 8 bits, ou seja, um único símbolo, letra ou número. Em programação, dados char são frequentemente utilizados para representar caracteres em um texto ou em uma sequência de caracteres, como uma string. Cada caractere é representado por um código numérico na tabela ASCII (ou outra tabela de caracteres), que é armazenado como um dado char em memória. Dados char também podem ser usados para representar símbolos especiais, como acentos, pontuação e caracteres de controle.

Float- Um exemplo de dado float em programação é: 3.1415927. O float é um tipo de dado numérico de ponto flutuante de 32 bits, o que significa que ele pode armazenar valores numéricos decimais com uma precisão moderada e com uma faixa de valores menor do que o double. Em programação, dados float são utilizados quando é necessário armazenar números decimais em um espaço de memória reduzido, com o objetivo de otimizar o desempenho do programa ou reduzir o consumo de memória. Dados float são menos precisos do que os dados double, mas ainda são capazes de representar valores decimais com uma boa aproximação. Alguns exemplos de uso de dados float em programação incluem cálculos matemáticos em jogos, simulações físicas e gráficos 3D. 

Boolean- Um exemplo de dado boolean em programação é o seguinte: true. O boolean é um tipo de dado lógico que pode ter apenas dois valores possíveis: true (verdadeiro) ou false (falso). Em programação, dados boolean são frequentemente utilizados para representar condições lógicas, como testes de igualdade, comparações numéricas e operações booleanas (como AND, OR e NOT). Dados boolean são úteis para controlar o fluxo de execução de um programa, decidindo quais partes do código devem ser executadas com base em condições lógicas. Eles também são usados para indicar o sucesso ou falha de operações ou funções. Por exemplo, em Java, a expressão "10 > 5" retorna true, enquanto "10 < 5" retorna false. 

Null- O null é um valor especial em programação que é usado para representar a ausência de um valor válido. Ele pode ser usado em diversos contextos, dependendo da linguagem de programação e do tipo de dado que está sendo manipulado. Em geral, o null é utilizado para indicar que uma variável ou um objeto não possui um valor definido ou não foi inicializado. Quando uma variável é declarada como null, ela não aponta para nenhum objeto ou valor válido na memória. O uso do null é importante para evitar erros em tempo de execução e para garantir a integridade dos dados em um programa. Alguns exemplos de uso do null em programação incluem a inicialização de ponteiros em C/C++, a referência de objetos em Java e a manipulação de valores nulos em bancos de dados.

Number- Um exemplo de dado number é: 123.456. Esse é um número decimal com três casas decimais e seis casas inteiras. Ele pode ser representado em várias formas, incluindo notação científica (1.23456 x 10^2) ou notação de engenharia (123.456E+0). Dados numbers são comumente usados em programação para representar números reais e realizar cálculos matemáticos precisos.

Bigint- O bigint é um tipo de dado numérico que pode armazenar valores inteiros muito grandes em programação. Ele é geralmente utilizado em linguagens de programação como Java, Python, C++ e outras, para permitir a manipulação de números inteiros que excedem a faixa de valores suportados pelos tipos de dados inteiros padrão, como int e long. Um exemplo de dado bigint em programação seria o valor 9223372036854775807, que é o valor máximo suportado pelo tipo de dado long em Java. Já com o bigint, valores ainda maiores podem ser armazenados, permitindo a realização de cálculos matemáticos complexos ou a manipulação de grandes conjuntos de dados inteiros. O bigint pode ocupar mais espaço em memória do que outros tipos de dados inteiros, mas oferece uma maior precisão e uma faixa de valores mais ampla.

String- Um exemplo de dado string em programação é o seguinte: "Olá, mundo!". A string é um tipo de dado que representa uma sequência de caracteres ou texto em programação. Ela pode conter letras, números, símbolos e espaços em branco, e é representada por uma série de dados char armazenados em sequência na memória do computador. Strings são frequentemente utilizadas para armazenar informações de texto em um programa, como mensagens de erro, títulos de página, nomes de usuários e senhas. Em programação, há uma série de operações que podem ser realizadas com strings, como concatenação (junção de duas ou mais strings), comparação de strings, busca de substrings e alteração de caracteres. Dados string são utilizados em praticamente todas as linguagens de programação, incluindo Java, Python, C++, JavaScript e muitas outras.

Symbol- O tipo de dado symbol é comum em algumas linguagens de programação, como Ruby e Clojure, por exemplo. Um exemplo de dado symbol em Ruby seria o seguinte: :nome. O symbol é um tipo de dado imutável que representa um nome ou identificador único em um programa. Eles são frequentemente utilizados em Ruby para representar chaves em hashes, como uma forma mais eficiente de identificação de uma chave, uma vez que symbols não precisam ser comparados da mesma forma que strings. Em Clojure, os symbols são usados para representar nomes de funções, macros e variáveis. Eles são armazenados na tabela de símbolos da linguagem e podem ser acessados e manipulados de forma programática. Em geral, o symbol é um tipo de dado que é útil em linguagens funcionais e de programação orientada a objetos, onde a identificação de nomes e identificadores é importante para o correto funcionamento do programa.
```
_Sintaxe dos dados_
``` 
Byte - int int1 = 128;
try {
   byte value1 = (byte) int1;
   Console.WriteLine(value1);
}

Short - Dim shortValue1 As Short = 1034
Console.WriteLine(shortValue1)

Dim shortValue2 As Short = &H040A
Console.WriteLine(shortValue2)

Dim shortValue3 As Short = &B0100_00001010
Console.WriteLine(shortValue3)

Int - int a = 123;
System.Int32 b = 123;

Long - long meuNumeroLong; 

Boolean - boolean minhaVariavelBooleana;

char - char meuChar;

float - float meuFloat;

double - double meuDouble;

null - MinhaClasse minhaInstancia = null;

number - int meuInteiro = 42;
double meuDouble = 3.14;

bigint - import java.math.BigInteger;

BigInteger meuBigInt = new BigInteger("123456789012345678901234567890");

string - String minhaString = "Olá, mundo!";

symbol - const meuSymbol = Symbol("meu simbolo");
```

Elementos do Android Studio
```





