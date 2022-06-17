# Git/Github  :book:

-  #### Introdução base de como funciona o GIT

1.  O funcionamento do git é constituído por 3 objetos as blobs que são os arquivos, as Tree que são as pastas e os commits que organizam e junto tudo no servidor GitHub ou em qualquer um de preferência.
2.  Todo esses processos são criptografados pela SHA1(Conjunto de 40 caracteres) onde houver qualquer alteração gerara uma chave diferente.

- #### Principais Comandos Git

  - **git init** (Inicia um repositório na maquina local).
  - **git remote add origin**  **(_Adicionar Url do diretorio criado no GitHub_)**  :arrow_forward:(seta uma conexão remota). 
  - **git config user.name " " ** **_(Adicionar nas apas seu nome do GitHub)_** :arrow_forward: (Seta o autor para apresentar nos commits).
  - **git config user.email " " ** **_(Adicionar nas apas seu email do GitHub)_** :arrow_forward: (Tambem seta nos commits e para localizar quem foi o autor).
  - **git add .** (Adiciona todos os arquivos na Stage no ciclo de vida do Git)
  - **git commit -m " "** **_(Adicionar nas apas a mensagem referente a modificação feita no projeto ou alguma nova função adicionada)_** :arrow_forward: (Esta etapa vai até Unmodified no clico de vida do Git para ser empurrado para servidor).
  - **git push origin master** (empurra para o servidor).
  - **git pull origin master**  (baixa arquivo do servidor e caso houver algum conflito o mesmo devera ser realizado para corrigir).

- #### Comando de Modificação Git

  - **git config --global --unset user.name ou user.email **(Comando para remover algum email ou nome que queira alterar).
  - **git config --list** (Verifica as configurações do seu git).
  - **git status** (Verifica as modificações que ouve no projeto).

  



 



