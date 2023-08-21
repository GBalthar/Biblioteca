### Instruções e Boas Práticas de Python

Bootcamp **Santander** 2023 - Ciência de Dados com Python

---

#### Requisitos

- Ter o Pyhton instalado na máquina.
- IDE (Visual StudioCode ou PyCharm)

- Não é feito para APP Mobile. É possível mas há linguagens muito melhores.

---

#### Comandos

- **print** - Imprime um texto. O texto tem que estar assim: ``print ("Hello World!")``
- **variável** - Basta atribuir um nome e o sinal de recebe, o igual. Exemplo: `` idade = 23 `` ou `` idade, nome = (23, 'Guilherme') ``
- **input** - Serve para que o usuário atribua um valor a uma variável. Exemplo: ``nome = input("Informe seu nome: ")``
- 

---

#### Funções

- **dir** - Retorna a lista de nomes no escopo local atual, basicamente as bibliotecas que temos instaladas. Se colocar dentro dos parênteses um objeto, a função irá retornar os dados sobre aquele objeto.
- **help** - Invoca o sistema de ajuda integrado, ou seja ele traz informações sobre o objeto em questão, é como se fosse um Google dentro do Python. Com isso, consultamos todos os métodos atrelados ao que estamos buscando.

---

#### Operadores

O código ``print(A *operador* B)`` retorna um resultado Booleano da afirmação entre A e B.

**Aritméticos**

- **Soma** - Símbolo "+".
- **Subtração** - Símbolo "-".
- **Divisão** - Símbolo "/".
  - **Divisão Inteira** - Símbolo "//". Retorna resultados inteiros.
  - **Resto** - Símbolo "%". Retorna o resto de uma divisão.
- **Multiplucação** - Símbolo "*".
- **Exponenciação** - Símbolo "**".



**Comparação**

- **Maior Que** - Símbolo ">".
  - **Maior ou Igual Que** - Símbolo ">=".
- **Menor Que** - Simbolo "<".
  - **Maior ou Igual Que** - Símbolo "<=".
- **Igual** - Símbolo "==".
- **Diferente** - Símbolo "!=".



**Atribuição**

- **Recebe** - Símbolo "=". É possível combinar um operador aritmético antes do "=" para fazer a modificação do valor atribuído à variável com uma operação matemática.

  Exemplo: ``A = 100 -> A += 10``. Ao final A valerá 110, ou seja 100 + 10.



**Lógicos**

- **E** - Símbolo "and".
- **Ou** - Símbolo "or".
- **Negação** - Símbolo "not". É sempre o inverso do verdadeiro.



**Identidade**

- **Is** - Serve para descobrir se duas variáveis têm o mesmo valor atribuído.
- **Is Not** - Serve para descobrir se duas variáveis não têm o mesmo valor atribuído. Segue a mesma lógica da negação (operador lógico).



**Associação**

- **In** - Serve para saber se um determinado valor pertence a uma variável que recebe uma lista.
- **Not In** - Serve para saber se um determinado valor não pertence a uma variável que recebe uma lista.

---

#### Tipos de Dados

O Python reconhece automaticamente os tipos de dados. Cabe a nós manipularmos os tipos de acordo com o uso que queremos. **O tipo de dado é de suma importância para o peso do programa**.



**Podemos mudar o tipo de uma variável para poder fazer operações diferentes usando o mesmo objeto. Basta colocar o nome do tipo antes do valor do objeto entre parênteses.**



- **Texto** - **str**. Deve ser usado entre aspas duplas ou simples.
- **Númerico**
  - **int** - Números inteiros
  - **float** - Números fracionados
  - **complex** - Números complexos
- **Booleano** - **bool**. 0 ou 1. Verdadeiro ou falso basicamente.

---

#### "Hacks" Aprendidos

- Se abrirmos o terminal do VS Code e escrevermos "python", está aberto o modo interativo do Python, onde podemos testar como funciona determinada função ou trecho de código rapidamente. Por aqui também podemos instalar bibliotecas com o "import".
- Usar *Snake Case* em Python. Exemplo: Total do Usuário vira total_usuario.
- Colocar constantes com tudo em CAPS. Assim você sabe que aquela variável não deve sofrer alterações. Lembrando, não podemos definir constantes com um comando em Python.


---

:white_check_mark: Por hora, é só, mas a intenção é sempre atualizar esse documento com novos aprendizados, provavelmente algo foi esquecido e será lembrado no futuro. :smile: