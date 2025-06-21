## Aula de Hoje 18/06/2025: Repositórios e versionamento com Git e GitHub
Hoje primeira aula de Backend, vou resumir os principais tópicos abordados sobre versionamento de código utilizando Git e GitHub.

## Tópicos Abordados

**Versionamento Git**
- O Git é um sistema de controle de versão que permite que múltiplos desenvolvedores trabalhem em um projeto simultaneamente, mantendo um histórico completo de alterações.

**Repositório Remoto no GitHub**
- O GitHub é uma plataforma de hospedagem de código que utiliza Git. Um repositório remoto no GitHub permite que você armazene seu código na nuvem, facilitando a colaboração e o compartilhamento.

**Configuração de Usuário e Email no Git**
- Para que o Git possa registrar suas alterações corretamente, é necessário configurar seu nome de usuário e email. Isso é feito com os comandos:
  ```
  git config --global user.name "Seu Nome"
  git config --global user.email "seuemail@example.com"
  ```

**Terminal e Comandos Básicos**
- O terminal é uma interface de linha de comando que permite interagir com o sistema operacional. Alguns comandos básicos do Git:
  ```
  git init
  ```

  ```
  git status
  ```

  ```
  git log
  ```
  entre outros.

**Git Add**
- O comando git add é utilizado para adicionar alterações, antes de realizar um commit. Por exemplo: 
  ```
  git add nome_do_arquivo
  ```
  ou para adicionar todas as alterações:
  ```
  git add .
  ```

**Git Commit**
- O comando git commit é usado para salvar as alterações no repositório. É importante incluir uma mensagem descritiva para documentar o que foi alterado:
  ```
  git commit -m "mensagem descritiva do commit"
  ```

**Git Push**
- O comando git push é utilizado para enviar as alterações do repositório local para o repositório remoto no GitHub. 
  ```
  git push origin nome_da_branch
  ```

**Git Pull**
- O comando git pull é usado para atualizar o repositório local com as alterações do repositório remoto. Ele combina os comandos 
  ```
  git pull origin nome_da_branch
  ```

**Git Branch**
- O comando git branch permite criar branches. As branches são usadas para desenvolver funcionalidades de forma isolada:
  ```
  git branch nome_da_nova_branch
  ```

**Git Stash**
- O comando git stash é utilizado para salvar temporariamente alterações não commitadas, permitindo que você mude de branch ou faça outras operações sem perder seu trabalho:
  ```
  git stash
  ```

## Conclusão

Hoje aprendemos conceitos fundamentais sobre o uso do Git e GitHub, que são essenciais para o desenvolvimento colaborativo de software. A prática desses comandos nos ajudará a gerenciar melhor nossos projetos e a colaborar de forma mais eficiente.