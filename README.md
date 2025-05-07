# CRIAÇÃO DE FUNÇÕES EM JS:

# -Declaration.

* Uma instrução que cria uma variavel, função ou outro objeto. uma declaração pode ser uma declaração de função, de variavel de classe e define a existencia e a inicialização de um elemento no código.

Exemplos: 

Var, let ou const.

**-Vantagens e desvantagens:**

* Flexibilidade na declaração, controle de escopo, constantes imutáveis e evita erros de redefinição.

* Mudança de comportamento de var, a necessidade de escolher a palavra-chave correta e compreensão do escopo.

 # -Expression.

* Uma expressão é uma unidade de códigos válida que resulta em um valor. existem dois tipos de expressões: aquelas que tem efeitos colaterais (como atribuir valores) e aquelas que avaliam.

 Exemplos: 
 
A expressão x = 7 é um exemplo do prmeiro tipo.

A expressão 3 + 4 é um exemplo do segundo tipo.

E tem as strings como "olá, mundo" uma string literal.

 **-Vantagens e desvantagens:**

* A facilidade de aprendizado, a compatibilidade com a maioria dos navegadores e a possiblidade de copiar efeitos e interações com o usuário.

* Riscos de segurança, problemas de desempenho e dificuldade de depuração.

 # -arrow.

* Uma forma mais concisa e sintaticamente mais elegante de criar funções, otimiza a escrita do código, deixando mais limpo, enxuto e aumentado a lengibilidade.

Exemplos:

const saudacao = nome => "olá, ${nome}!";
console.log(saudacao("joao")) ; // saida: olá, joao!

const dobrar = valor => valor * 2;
console.log(dobrar(10)) ; saida: 20

const soma = (a , b) => a + b;
console.log (soma(5 , 3)); // saida: 8

**-vantagens e desvantagens:**

* Sintaxe mais curta, retorno implicito e código mais limpo e previsível.

* Não são construtores, não são ideais para metodos com contexto dinamico.
