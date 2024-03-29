### Instruções e Boas Práticas Para o Uso do CSS

**OBS:** Lembrando que o Markdown se confunde com os comandos do HTML, portanto os ">" finais serão substituídos por "^".

---

#### Requisitos

- Editor de texto (ex: Notepad++)
- Navegador de internet (ex: Chrome)
- Os arquivos HTML e CSS devem estar na mesma pasta

---

#### Preparação no HTML

- **<link ref="stylesheet" href="Style.css"** - Adicionar esse comando dentro do ***head*** do arquivo HTML para referenciar o arquivo HTML ao arquivo CSS chamado *Style.css*
- **ID** - Damos IDs para elementos que não queremos que se repitam dentro do site. Fazemos isso seguindo o exemplo: **<h1 id="title"^Guilherme Balthar</h1^**
- **Classe** - Damos classes aos elementos que queremos estabelecer um padrão para todos daquela mesma classe. Fazemos isso seguindo o exemplo: **<h2 class="subtitle"^Posts</h2^**

---

#### Procedimento no CSS

- **Elementos** - Com os comandos "#" para ID e "." para classe, adicionamos os elementos desejados, por exemplo: **#title, .subtitle**. Assim adicionamos o ID *title* e a classe *subtitle* aos elementos do CSS
- **Comentários** - Para escrever comentários, use /**/ e tudo que estiver entre os asteriscos será um comentário

---

#### Customizações

Para customizarmos os elementos, abrimos chaves logo depois dos elementos (não esqueça de fechá-las se o editor não o fizer automaticamente), veja: **#title, .subtitle {**. Dentro das chaves, damos um TAB para identar e podemos customizar com os seguintes passos:

- **Texto**

  - **color: *exemplo* ;** - A cor da fonte mudará para a cor *exemplo*
  - **font-size: 10px ;** - O tamanho da fonte mudará para 10 pixels
  - **font-style: *italic* ;** - O estilo da fonte mudará para *itálico*
  - **font-family: *arial* ;** - O tipo da fonte mudará para *arial*
  - **font-weight: bold ;** - A fonte ficará em negrito
  - **text-decoration: *exemplo*:**  - Coloca uma linha em algum lugar do texto conforme o completado no lugar de exemplo, veja:
    - underline - Linha abaixo do texto
    - overline - Linha acima do terxo
    - line-through - Linha cortando o texto
  - **text-align: *exemplo* ;** - Esse comando irá alinhar o texto conforme o que for completado no *exemplo*
    - center - Alinha o texto centralizado
    - left - Alinha o texto à esquerda

- **Borda**

  - O comportamento das bordas tem diferentes camadas. Podemos editar cada uma delas dentro do CSS com os comandos da imagem abaixo:

  <img src="data:image/png;base64,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">

  - **margin** - Altera a distância da borda para a margem da tela (ex: **margin: 10px;**)
  - **border** - Altera a espessura, a linha e a cor da borda (ex: **border: 3px solid #000;**)
    - Nota-se que #000 é o código para uma cor, no caso, preto
    - Pode-se usar os tipos *solid*, *dotted* e *dashed* para a linha da borda
    - É possível aredondar os cantos da borda usando o comando ***border-radius*** (ex: )
  - **padding** - Altera o tamanho da caixa que limita a borda (ex: **padding: 10px;**)
    - Podemos adicionar mais dimensões para a caixa (ex: **padding: 10px 5px 10px 5px;**)

- **Background** - Para mudar a cor do fundo do elemento, usamos o comando **background: #FFF;**. Nesse caso a cor é branco.

  - Para alterar o fundo da página inteira, sem ser em uma parte específica (como o *article*, por exemplo), usamos o elemento ***body*** (ex: **body {background: #ccc;}**). Nesse caso, a cor é cinza.

- **Lista**

  - **list-style-type: *exemplo;*** - Muda o tipo do tópico da lista conforme o que é posto no lugar de *exemplo*
    - square - Um quadrado
    - upper-roman - Algarismo romano (para listas ordenadas)
    - código - É possível colocar emojis, por exemplo
  - **list-style-image: url("site.png") ;** - Adiciona uma imagem vinda da URL indicada no lugar do tópico

- **Alinhamento** - É importante dar alinhamento ao *body* do site. Para isso usamos:

  - **max-widht: 900px ;** - Esse comando dará um espaçamento confortável para que o conteúdo do site fique centralizado e se adeque caso a tela fique pequena demais. Pode-se testar outros tamanhos de pixels
  - **margin: auto ;** - Isso irá colocar tudo que for criado de forma centralizada de acordo com o *width* que for escolhido

---

#### Finalidade

- O CSS é um recurso capaz de padronizar a página, então é recomendado que sejam criados comandos para que o layout da página se mantenha "bonito" sem que seja preciso alterar os códigos sempre que um novo elemento for criado.

---

#### Responsividade

- A partir de certo ponto, a tela responsiva não se adequa corretamente ao navegador. Para isso, usamos alguns comandos para restringir a responsividade e fazer com que a página se comporte de forma diferente a partir de certo ponto. Estudar @margin.

---

#### Flexbox

- 

---

#### "Hacks Aprendidos"

- **a** - O elemento *a* no CSS é referente aos links
- ***** - O * no CSS refere-se à página inteira
- **box-sizing: border-box** - Esse comando restringe os elementos ao limite do elemento onde ele está inserido, ou seja, ele não irá ultrapassar "caixinhas"
- **Variáveis** - O CSS permite a criação de variáveis para que não seja preciso escrever linhas enormes de código ou ficar lembrando o código das cores
  - **:root {--cor: #000}** - A variável *cor* foi criada contendo a cor #000
  - **var(--cor)** - É o comando que chama a variável
- **Hover** - Para adicionar o efeito de mudança de cor ao passar o mouse sobre o texto, usamos o comando hover
  - **header nav a:hover{color: gold;}** - Nesse exemplo, todos os comandos pertencentes ao header que contém um navegador (nav) e um link (a), ficam da cor *gold* quando o mouse passa sobre eles
- **Font Awesome** - Site que permite criar botões com ícones personalizados
- **Owl Carousel** - Site com comandos Java Script que permitem a criação do efeito *carrossel* através de JQuery
- **Loading.io** - Site que traz ícones animados para adicionar ao site


---

:white_check_mark: Por hora, é só, mas a intenção é sempre atualizar esse documento com novos aprendizados, provavelmente algo foi esquecido e será lembrado no futuro. :smile:
