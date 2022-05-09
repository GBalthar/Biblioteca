### Instruções e Boas Práticas Para o Uso do Bootstrap

**OBS:** Lembrando que o Markdown se confunde com os comandos do HTML, portanto os ">" finais serão substituídos por "^".

---

#### Requisitos

- Editor de texto (ex: Visual Studio Code)
- Navegador de internet (ex: Chrome)
- Os arquivos HTML, CSS e o download do Bootstrap devem estar na mesma pasta

---

#### Preparação no HTML

- Preparamos o HTML normalmente seguindo a estrutura básica e abaixo do título, inserimos **<link ref="stylesheet" href="Style.css"^** dentro do ***head*** para referenciar o arquivo HTML ao arquivo CSS chamado *Style.css* e **<link ref="stylesheet" href="bootstrap/css/bootstrap.min.css"^** para adicionar a biblioteca *bootstrap.min.css* do Bootstrap ao arquivo.
  - A biblioteca do Bootstrap contém códigos prontos de CSS para utilizarmos. Temos pré-visualizações dos layouts no site do Bootstrap para sabermos o que está sendo adicionado.


---

#### Procedimento

- Usamos a barra lateral do site do Bootstrap para buscar os efeitos e layouts. Vamos copiar e colar os códigos na sessão que queremos em nosso HTML

---

#### Customizações

- Usamos o arquivo CSS para alterar as classes nativas do Bootstrap, mudando os atributos que aprendemos nas aulas de CSS. É preciso ter atenção para as configurações que são importadas do Bootstrap, pois elas podem sobrepor as alterações que queremos fazer no CSS
- **Colunas** - No Bootstrap o uso de colunas para posicionarmos diferentes conteúdos é usual. Para usá-las, vejamos um exemplo:
  - ^div class="row">
        ^div class="col-lg-4">
            ^img src="exemplo.png" width="150">
        ^/div>
    ^/div>
    - As colunas são orientadas pela segunda linha do código, portanto a imagem *exemplo.png* entrará respeitando um espaçamento de 3 colunas, pois o Bootstrap divide a tela em, no máximo, 12 espaços. (então 12/4 = 3 colunas). O *lg* se refere ao tamanho "large" da coluna. Esse código deixa as imagens responsivas ao tamanho da janela, para que não sumam
    - Vale ressaltar que o tamanho da imagem pode ser alterado com o uso do comando ***width***

---

#### "Hacks Aprendidos"

- **Links Úteis**
  - **Orientações do Bootstrap** - https://getbootstrap.com/docs/5.1/components 
  - **Imagens Livres de Royalties** -  https://www.pexels.com/pt-br/
  - **Cores HTML** - https://htmlcolorcodes.com/
- **text-center**: Uma classe que alinha o texto ao centro da página automaticamente
- **container-fluid**: Uma classe que deixa o texto pegando a página inteira, ou seja, se a janela estiver pequena, ele se ajusta
- **Reposicionamento de Imagens** - Se uma imagem não fica exatamente onde queremos, podemos reposicioná-la com o uso do CSS. Através da criação de uma classe para a imagem, abrimos o comando ***position*** e atribuímos a variável ***relative*** caso a imagem esteja seguindo alguma orientação ou ***absolute*** caso ela esteja livre. Daí, usamos os comandos ***left***, ***right***, ***top*** e ***bottom*** para reposicioná-la com um número de pixels.

---

:white_check_mark: Por hora, é só, mas a intenção é sempre atualizar esse documento com novos aprendizados, provavelmente algo foi esquecido e será lembrado no futuro. :smile:
