### Instruções e Boas Práticas de JavaScript

---

#### Requisitos

- Editor de texto (Visual StudioCode)
- Navegador (Chrome) para aplicar em páginas
- Node.js para rodar comandos *node*
- Função *script* no HTML para inserir o documento *.js*. Recomenda-se colocar essa função no fim da página para carregar a página mais rápido.

---

#### Estrutura

- **Map** - 
- **Objeto** - 
- **Set** - 
- **Array** - 

---

#### Comandos

- **.get**
- **consult**
- **return**
- **console.log** - É um comando que apresentará uma reação para uma ação feita na página. Um clique ou a inserção de um valor, por exemplo.

---

#### Tipos de Erros

- **Error do EXMAScript** - Ocorre em tempo de execução e porque o código tem algum erro de digitação.
- **DOMException** - Erros referentes à árvore da estrutura de elementos do código de uma página da web.
- **Throw** - Ao invés de retornar uma *string* qualquer, retorna uma *string* com comportamento de erro.
  - **Return** - Retorna uma *string* qualquer.
- **Try e Catch** - Funções que identificam (*try*) e dão respostas (*catch*) aos erros
- **Finally** - É um bloco que é executado de qualquer maneira para divulgar o resultado do código.

---

#### Assicronicidade

- **Promises** - São dados recebidos que só se saberá se foram aprovados ou rejeitados depois de um certo período.
  - Pending, Fulfilled e Rejected são seus possíveis estados.
- **Async** - Entra antes da função que será uma *promise* informando que o código passará a rodar de forma assícrona naquela função
  - **Await** - Serve para parar o código e fazer a função *async* funcionar corretamente.

---

#### APIs

- São uma forma de intermediar os resultados do back-end com o que acontece no front-end.
- **Método Fetch** - 

---

#### Orientação a Objetos

- Getters e Setters podem ser usados como modificadores de um valor
- Caso um parâmetro tenha getters e setters,  por convenção, deve ser nomeado com o sinal _ como prefixo (ex:_exemplo)
- Método **super()** - Volta com informações para o objeto pai

---

#### Métodos

- **Método Map** - Cria um novo *array* a partir de uma função aplicada em um *array* original na ordem em que aparecem os valores
  - **array.map (callback, thisArg)** - O *callback* é onde entra a função que irá definir os parâmetros para a criação do novo *array*. Já o *thisArg* é opcional, ele serve para orientar a ação a algum objeto
- **Método Filter** - Cria um novo *array* a partir de um filtro aplicado no *array* original
  - **array.filter (callback, thisArg)** - Funciona da mesma forma que o Map. Um bizu é usar o comando *.includes* para pegar parte de *strings* de dentro do *array**
- **Método Reduce** - Executa uma função em todos os valores do *array*, mas retorna apenas um valor único.
  - **array.reduce (callbackFn, initialValue)** - O *callback* segue sendo a função a ser executada. Já o *initial value* é opcional também e é um valor sobre o qual o retorno final irá atuar.
- **Manipulação e customização do DOM** - 

---

#### "Hacks" Aprendidos

- **Arrow Function ((nome) =>)** - Esse símbolo serve para a mesma coisa que escrever *function nome {}*
  - **var -> valor** - Atribui um *valor* a uma *variável*.


---

:white_check_mark: Por hora, é só, mas a intenção é sempre atualizar esse documento com novos aprendizados, provavelmente algo foi esquecido e será lembrado no futuro. :smile: