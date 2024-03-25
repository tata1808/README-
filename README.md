# README-
  Principais Funções do GIT e GITHUB
  
  O Github é uma “rede social dev” em que é possível armazenar e compartilhar projetos de desenvolvimento de software. O Git é um sistema de controle de versão de arquivos; em outras palavras, é responsável por guardar o histórico de alterações sempre que alguém modificar algum arquivo que está sendo monitorado por ele. O GithHub armazena projetos de código aberto, ou seja, quem podem ser editados por outros programadores em um trabalho coletivo.
  Exemplos: Colaborar com grupos, gerenciar a associação e convidar usuários para participar, gerenciar funções da organização, gerenciar acesso ao repositório, organizar membros em equipes, gerenciaracesso ao project, gerenciar acesso programático, gerenciar acesso de OAuth. 
  
  Comandos do GITHUB
  Irei mencionar e desenvolver os príncipais comandos git que você precisa conhecer para gerenciar projetos,seja no github, seja em outras plataformas. 
  Para executar esses comandos git, basta abrir o prompt de comando ou CMD no seu computador. Usarei o github como exemplo de repositório:
  
  1. Git Commit: O commit é um comando importantíssimo. Ele leva as mudanças de um ambiente local para o repositório no git,permitindo ainda a inserção de uma tarefa, a pessoa desenvolvedora pode submeter seus feitos e deixar claro para outras pessoas o que ela fez.
  2. Git Add: Um comando muito similar ao "commit", ou seja, para subir para o repositório na web. É possível adicionar um único arquivo ou todos os arquivos modoficados de uma única vez.
     Para um único arquivo, use "git add nome_do_aqruivo". Para reparar todos os aequivos para atualização (incluindo as exclusôes), use "git add -A". Para preparar soemnte as adições,use "git add".
   3. Git Init: O init é o primeiro dos comandos git que se usa para começar um repositório. Isto é, o que ele faz é transformar uma pasta com códigos no seu HD em uma pasta monitorada pelo git, que será carregada para a plataforma e estará visível para outras pessoas. Ou então cria um repositório novo, do zero. Exemplo: "git init".
   4.  Git Clone: Para começar, muitas pessoas optam por uma alternativa ao init: o git clone. A partir dele, você clona um código de um repositório para a sua máquina para então começar a trabalhar nele. Pode ser um projeto de uma pessoa da sua empresa, um projeto de uma pessoa da sua empresa, um projeto de colegas da faculdade ou até mesmo uma aplicação open-source para qual você julgou interessante colaborar.
   5.  Git Status: Para saber algumas informações sobre a ramificação na qual você está trabalhando, agora use o "status". Esse comando esclarece quais arquivos foram alterados e faz alguam comparação com relação a ramificação principal. Exemplo: "git status".
   6.  Git branch: Falando em ramificações, precisamos falar logo sobre o termo branch. Para trabalhar em equipe, você pode criar diferentes branches, e o git administra todas elas em paralelo para evitar problemas de versão. Então, posteriormente, com um comando que veremos, é possível unificar as ramificações. O comando "git branch"  cria novas branches. Mas tambèm pode funcionar como uma forma de verificar as ramificações já existentes.
      
     Depois de criar uma, você precisa de um "push" para subir essa ramificação.
     
     Assim: “git push -u <remote> <nome-da-branch>”.

     Por sua vez, para deletar uma branch, use:

     git branch -d <nome-da-branch>

  7. Git Merge: Depois de programar em uma branch, você tem que fazer uma conjunção dela com outras para de fato subir as alterações. É só colocar o nome da branch que desejamos mesclar com a principal depois do termo merge.

  8. Git Checkout: Para fazer o merge corretamente, é preciso olhar esse outro comando, o checkout. O objetivo dele é fazer a pessoa programadora mudar de branch. Você pode usar o "git branch"   para saber quais existem e depois trocar de uma para outra.
     É importante destacar que é preciso fazer um checkout para a master branch quando queremos captar as mudanças de outra ramificação.

9. Git Revert: O revert é um dos comandos git aplicados para garantir a segurança dos nossos projetos. Permite desfazer algum commit e recuperar uma versão saudável, seja localmente, sej a remotamente.
    Para usá-lo, é preciso primeiro executar um “git log -- oneline” para obter o número do hash. Com o hash, então, é possível digitar: “git revert 'nº do hash'”.

10. Git Rm: O git rm é um comando muito útil para remover arquivos do git e parar de monitorá-los, ou seja, de associá-los ao repositório.
    
11. Git Pull: Antes de começar a programar em alggum repositório, é bom também executar um “pull”. Esse comando traz para a sua máquina todas as mudanças que foram realizadas na plataforma. Ou seja, é uma forma de atualizar a sua versão da aplicação com o que foi alterado remotamente.
    
12. Git Stach: O stash serve para criar uma pilha de alterações que serão enviadas posteriormente para o repositório. É uma boa forma de guardar algumas mudanças em espera enquanto você muda de branch para trabalhar em outros aspectos do sistema. É ideal para sistemas grandes, com muitas ramificações que demandam essa flexibilidade da pessoa programadora. Exemplo: “git stash”.
    
13. Git Config: O config é um comando inicial para vincular o trabalho no repositório com sua conta no github. Assim, é configurado com o nome e com o e-mail.
    
14. Git Reset: O reset é outra forma de voltar ao último estado saudável do seu sistema, uma alternativa ao revert. Funciona assim: “git reset --hard HEAD~1”.
    
15. Git Push: O push serve para subir as alterações de uma ramificação para um certo repositório. Ele entrega todos os commits e a mensagem. Exemplo: “git push”.





 



 
