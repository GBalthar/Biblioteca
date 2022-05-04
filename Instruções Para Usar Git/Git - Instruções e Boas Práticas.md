### Instruções e Boas Práticas Para o Uso do Git

---

#### Comandos Simples

- **dir** - Lista os diretórios presentes dentro daquela pasta
- **cd** - Abre a pasta de nome que sucede o comando
  - **cd ..** - Retrocede uma pasta
  - **TAB** - O TAB do teclado será útil para completar nomes de pastas
  - **CTRL + L** - Esse atalho do teclado será útil para limpar a tela quando ela estiver muito poluída
- **mkdir** - Cria uma pasta e a nomeia com o que for posto entre aspas (" ") na sequência do comando.
- **echo** - Retorna o texto escrito após o comando
  - **echo texto > nome.txt** - Cria um arquivo .txt chamado "texto"

---

#### Comandos Git

- **Git Init** - Cria um repositório. É a primeira ação a se fazer, esse comando irá criar uma pasta oculta .git onde serão armazenados todos os códigos e ações que acontecem "por detrás das cortinas" no Git.
- **Git Status** - O Git retorna como está o status do programa, ou seja, se está tudo em ordem ou se algo precisa ser adicionado e comitado
- **Git Add** - Adiciona o arquivo, colocando-o na situação de *staged*, ou seja, aguardando para ser comitado
  - **Git Add .** - Adiciona todos os arquivos da pasta de uma vez
- **Git Commit** - Comita o arquivo, colocando o programa em ordem para ser atualizado
  - **Git Commit -m** - Coloca uma mensagem ao comitar o código. É uma boa prática importante para alinhar tudo que está sendo feito e atualizado no código.
- **Git Push** - Envia o arquivo para alinhá-lo com os anteriores. É necessário inserir o link para onde o arquivo irá se isso ainda não foi feito pelo comando Git Clone ou Git Pull.
  - **Git Push origin main** - Envia o arquivo para o destino antes informado (representado por ***origin*** no comando). ***Main*** é a branch que será enviada, ou seja, o local onde está sendo trabalhado o código. Ela fica localizada no Git após o nome de local do arquivo.
- **Git Clone** - Clona o programa cujo link é informado na sequência do comando.

---

#### "Hacks Aprendidos"

- **rm -f .git/index.lock** - Comando para *descrashar* o Git quando aparecer o seguinte erro: *"Another git process seems to be running in this repository, e.g. an editor opened by 'git commit'. Please make sure all processes are terminated then try again. If it still fails, a git process may have crashed in this repository earlier: remove the file manually to continue."*

---

:white_check_mark: Por hora, é só, mas a intenção é sempre atualizar esse documento com novos aprendizados, provavelmente algo foi esquecido e será lembrado no futuro. :smile:

