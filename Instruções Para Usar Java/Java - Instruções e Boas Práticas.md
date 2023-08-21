### Instruções e Boas Práticas de Java

---

#### Requisitos

- Visual Studio Code
- Plug-In Java Debugger
- JDK

---

#### Estrutura

- Declaração de Classes - A estrutura de uma classe em Java se dá pelo comando **public class *Nome da Classe* {}** .

- Importação de Classes - Para trazer uma classe para dentro de um código, é necessário utilizar o comando **import *caminho da classe***.

- Modificadores de Acesso - Definem os atributos que podem ser acessados ou não.

  - **public** - Qualquer classe pode acessar.
  - **protected** - Qualquer classe definida no mesmo pacote (**package** - é a pasta onde se encontra o arquivo do código) ou subclasse tem acesso. Se não houver modificador, assim será o comportamento padrão.
  - **private** - Apenas a própria classe acessa.

- Estruturas de Condição - São funções condicionais do Java.

  - **if & else** - Condição do se e se não padrão.

  - **switch / case** - Condição de retorno em casos específicos.

    **switch** (*variável*) {

    **case** *Caso 1*

    **case** *Caso 2*

    **default:** *Retorno padrão*

    }

    Pode - se adotar quantos casos forem necessários. O ***default*** é o retorno padrão caso nenhum dos casos for contemplado.

- Estruturas de Repetição - São funções do Java que permitem um *loop* controlado pelo código.

  - **while** - Repete a função do código até que uma determinada condição seja satisfeita.
  - **do / while** - Repete a função do código enquanto uma determinada condição está sendo satisfeita.
  - **for** - Repete a função do código até que seja satisfeita uma condição final. Ele se difere do *while* porque permite que sejam definidos o início da contagem e de quanto em quanto será feita a contagem.
  - **enhanced for** - 


---

#### Boas Práticas

- Comentários - São feitos com "//" em linha e com "/**" no início e "asterisco/" no fim em bloco.
- JavaDoc - São comentários que são exportados para a leitura do código por outros desenvolvedores terem maior conhecimento sobre o que está escrito.

---

#### Variáveis

- As variáveis são compostas por visibilidade, modificador, tipo, nome e valor inicial.
  - Visibilidade: *public*, *protected* e *private*. Estão ligadas à orientação a objetos.
  - Modificador: *static* e *final*. *Static* está ligado à orientação a objetos, já *final*, está dizendo que aquela variável é constante, ou seja, não irá mudar.
  - Tipo: Tipo de dado
    - Textual - Armazenam texto (*char* e *string*, que é o mais usado, com seu conteúdo entre aspas duplas).
    - Numeral - Armazenam números (*byte*, *short*, *int*, *long*, *float* e *double* são os tipos do menor para o maior armazenador de dados).
    - Lógico - Verdadeiro ou falso (*boolean*).
    - Objeto - Relacionado à orientação a objetos.

  - Nome: Nome dado à variável pelo desenvolvedor.
  - Valor Inicial: Caso deseje, a variável pode ter um valor inicial.

- Apenas tipo e nome são sempre obrigatórios, o resto depende do que está sendo criado.
- Não são permitidos espaços nos nomes das variáveis e nem iniciar os nomes com letras maiúsculas.

---

#### Operadores Aritméticos

- Pós-Fixado - Faz uma operação de forma tardia. Exemplo: **exp++** :arrow_right: irá somar uma unidade à expressão após ela ser usada.
- Pré-Fixado - Faz uma operação de forma antecipada. Exemplo: **++exp** :arrow_right: irá somar uma unidade à expressão antes de ela ser usada.
- Aritmético - Soma (+), Subtração (-), Multiplicação (*), Divisão (/) e o Resto da Divisão (%).
- Atribuição - Simples (=), Com Operação (+=, -=, =*, /=, %=).

---

#### Métodos

- São funções de código estabelecidas pelo desenvolvedor. Para criar um, é preciso passar o seguinte comando (para métodos iniciais aprendidos): **public static *tipo de retorno nome do método* (*parâmetros*) {*corpo*}**. Exemplo: public static void soma () { int numero1 + int numero2 }.
- Para que o método dê um retorno, é preciso chamá-lo através de uma classe ou objeto. Por exemplo: Se o método exemplificado acima estiver nomeado como "Calculadora", isto é, o nome do arquivo que contém o método é este, então o comando *System.out.println(Calculadora.soma (3, 4))* retornará 7. No caso do objeto: *usuario.getEmail()* provavelmente retornará o email do objeto "usuário" em questão.
- Sobrecarga - Os métodos podem ser reaproveitados quando passamos parâmetros diferentes para um mesmo método. Para isso, devemos adicionar parâmetros ou mudar os tipos de retornos dos mesmos. Exemplo: Usamos um mesmo método para calcular áreas de diferentes formas geométricas.
- Retorno - Representado pela palavra **return**, o retorno serve para parar o código, e é opcional. Ele deverá retornar um objeto do mesmo tipo que o do método.

---

#### Operadores Relacionais e Lógicos

- Relacionais - Comparam dois operandos.
  - Similaridade - Diz respeito à igualdade (==) ou à diferença (!=) entre dois operandos.
  - Tamanho - Diz respeito ao tamanho maior (>) ou menor (<) entre dois operandos. Podendo usar também maior/menor igual (<= e >=)

- Lógicos - Realizam comparações lógicas entre operandos.
  - Conjunção - Operação lógica que se confirma quando ambos os operandos são verdadeiros (&&). O caso "e".
  - Disjunção - Operação lógica que se confirma quando um dos operandos é verdadeiro (||). O caso "ou".
  - Disjunção Exclusiva - Operação que só se confirma quando os operandos são opostos (^).
  - Negação - Operação que inverte o valor lógico de um operando (!), ou seja, se for verdadeiro, a leitura será falsa, e vice-versa.


---

#### Orientação a Objetos

- Encapsulamento - Proteção dos dados do código.
- Abstração - Preocupar-se com as características essenciais.
- Reuso - Possibilidade de reutilizar o código com a separação dos objetos.
- Estrutura Básica
  - Classe - Estrutura de molde e representação do conceito do mundo real. São substantivos e têm nomes significativos, que se relacionam com o seu objetivo. Usa-se o código **class** *Nome* {}.
  - Atributo - Elemento de uma classe, responsável por definir sua estrutura de dados. São as características da classe. Usa-se o código *Tipo de Dado* *Nome* dentro dos colchetes da classe. Exemplo: int portas = 10.
  - Método - Porção de código disponibilizada pela classe. São as ações que as classes podem executar. Usa-se o código *Tipo de Dado* *Nome da Ação*. Exemplo: void abrir ( ) { }.
    - Construtor - Constrói objetos, por exemplo, são passados parâmetros para definir o objeto, como o número de portas se não tiver sido informado. Utilizamos os comandos de **get** e **set** nessa fase do código do método.
    - Destrutor - Libera recursos da máquina, auxiliando na destruição dos objetos já utilizados.

  - Objeto - Representação de um conceito ou entidade do mundo real. Ele se diferencia da classe porque o objeto é mutável, a classe é estática. Usa-se o comando **new** para criar um objeto.
  - Mensagem - É o processo de ativação de um método de um objeto. Ocorre quando uma requisição dispara a execução do método. Para chamar a execução do método, utiliza-se o código *Classe* ou *Objeto*.<*Método*>.

- Relações
  - Herança - É um relacionamento entre classes em que uma subclasse é considerada filha de uma superclasse considerada classe mãe. Com isso, a classe filha herda atributos e métodos (membros) da classe mãe. Código usado: **class** *Filha* **extends** *Mãe* { ... }.
    - Upcast - É quando transformamos uma classe filha (mais específica) em uma classe mãe (mais genérica). Usamos o código: *Mãe* *variável* = **new** *Filha* ();
    - Downcast - É quando transformamos uma classe mãe (mais genérica) em uma classe filha (mais específica). Essa operação não é muito usada e geralmente dá erro. Usamos o código: *Filha* *variável* = (*Filha*) **new** *Mãe* ();
    - Polimorfismo - É quando uma mesma ação pode ser realizada de várias formas, por exemplo, um pagamento pode ser feito em dinheiro, crédito ou débito.
    - Sobrescrita - É quando uma mesma ação varia o seu resultado conforme mudam as chamadas de diferentes objetos, acrescentando características. Por exemplo, se é pedida uma ação de exibição de saldo em uma conta bancária, é possível mostrar o saldo bruto ou o saldo com dedução de IOF.

  - Associação - Possibilita um relacionamento entre classes, permitindo a interação e a resolução dos objetivos de forma conjunta.
    - Estrutural - É quando há dependência entre objetos. 
      - Composição - Se um morador deixa de existir, seus dados também vão deixar de existir para o condomínio.
      - Agregação - Se uma disciplina deixar de existir, um aluno não vai deixar de existir.

    - Comportamental - É quando um método depende de uma classe para acontecer. Como a emissão de uma nota fiscal, que depende da compra.

  - Interface - Define um contrato que deve ser seguido pela classe que implementa a interface, comprometendo-se a realizar os comportamentos da interface. Por exemplo, uma impressora funciona em qualquer sistema operacional porque ela tem uma interface, oferecendo métodos próprios para serem usados independentemente do sistema. Para criar uma interface, usamos: **interface** *A* { ... }. E para relacionar a interface a uma classe, usamos: **class** *B* **implements** *A* { ... }.

- Pacotes - Organização física ou lógica criada para separar classes com responsabilidades distintas. Usamos pastas para organização. Para chamar os pacotes, usamos: **package** para criar e **import** para usar.
- Visibilidades - Sua finalidade é determinar até que ponto uma classe, atributo ou método pode ser usado. São o **public**, **private** e **protected** em Java.

---

#### Spring Boot

- É um setup que traz todas as configurações iniciais do sistema para que seja economizado o tempo configurando o sistema.

---

#### "Hacks" Aprendidos

- Case-sensitive - O computador interpreta textos iguais, com letras maiúsculas e minúsculas diferentes, como duas coisas distintas. Exemplo: Nome é diferente de nome, que são diferentes de NOME.
- GitHub Professor Thiago Leite - https://github.com/tlcdio/OOAula03.4/blob/master/src/one/digitalinnovation/oo/Carro.java (Aula de Orientação a Objetos)


---

:white_check_mark: Por hora, é só, mas a intenção é sempre atualizar esse documento com novos aprendizados, provavelmente algo foi esquecido e será lembrado no futuro. :smile:



:construction: **WORK IN PROGRESS** :construction: