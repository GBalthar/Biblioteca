### Instruções e Boas Práticas Para o Uso do HTML

---

#### Requisitos

- Editor de texto (ex: Notepad++)
- Navegador de internet (ex: Chrome)

---
#### O Básico
- Elemento HTML

<img src="https://mdn.mozillademos.org/files/9347/grumpy-cat-small.png">

- Estrutura (Aspas e a falta ou substituição do ">" pelo "^" ao final dos comandos foram usados para o editor de Markdown não se confundir)
  - "<!DOCTYPE html" :arrow_right: Orientação ao navegador do que será escrito
  - "<html" lang="pt-br" :arrow_right: Informa o idioma da página
    - "<head" :arrow_right: Cabeçalho do site 
      - "<meta" :arrow_right: Codificação dos caracteres
      - "<title^Exemplo</title" :arrow_right: Coloca o título *exemplo* na aba do navegador
    - "</head"
    - "<body" :arrow_right: Corpo do site
    - "</body"
  - "</html" :arrow_right: Nota-se que "<x" abre e "</x" fecha um campo

---

#### Semântica

- **"<section"** - Representa uma seção, uma lista de coisas que entrarão ali
- **"<header"** - Representa o cabeçalho da página
- **"<article"** - Representa um item da seção
- **"<aside"** - Representa uma barra lateral
- **"<footer"** - Representa o rodapé da página
- **"<h1 a <h6"** - Dá um tamanho (1 grande para 6 pequeno) aos caracteres dentro do comando

---

#### Textos e Links

- **"<p"** - Esse comando suporta textos densos que podem conter imagens e links
- **"<a"**- Esse elemento é uma âncora, serve para atribuir links e ações para interação do usuário
  - **"<a href= "site.com"^ Site </a"** - Esse comando cria um hiperlink para a palavra "Site" contendo o endereço *"site.com"* **(Note que o comando /a não foi colocado com > para que o editor de Markdown não se confundisse)** Esse mesmo comando pode apontar também para:
    - E-mails - mailto:guilherme@gmail.com
    - Telefones - tel:21988013333
  - **"<a href= "site.com" target=_ blank^ Site </a"** - O comando ***target=_blank*** irá abrir o *link* em uma nova aba

---

#### Imagens

- Criar uma pasta chamada *img* dentro da pasta contendo o arquivo HTML
- **"<img src="img/exemplo.jpg"^"** - Obrigatório para trazer a imagem referenciada
- **"<img src="img/exemplo.jpg" alt="Foto Exemplo"^"** - Esse comando mostra um texto para o usuário entender o que a imagem significa caso a imagem não carregue. É muito recomendado tê-lo, mas não não é obrigatório

---

#### Listas

- **"<ul"** - Lista desordenada
- **"<ol"** - Lista ordenada
- **"<li"** - Item da lista

---

#### "Hacks Aprendidos"

- Tiny PNG - O site *tinypng.com* diminui bastante o arquivo de imagem, é interessante usá-lo para economizar espaço

---

:white_check_mark: Por hora, é só, mas a intenção é sempre atualizar esse documento com novos aprendizados, provavelmente algo foi esquecido e será lembrado no futuro. :smile:
