# Aula - GitHub!

# O que é Git e GitHub?
  Git e GitHub são utilizados no dia a dia dos programadores por um motivo bem simples: ter uma forma fácil de gerenciar o código fonte da aplicação do sistema e do produto.
  Além disso, ele ajuda os times a trabalharem de forma mais rápida e inteligente. Isso acontece pois a ferramenta de controle de versão mantém um registro de todas as versões do código, ou seja, de todas as modificações. Isso ajuda a pessoa que desenvolve a conseguir voltar para qualquer versão anterior ou compará-las, ajudando a descobrir e corrigir erros muito mais rápido.

# O que são repositórios, commits e branches?

## Repositórios

  Um repositório, ou repo, é um diretório onde você armazena os arquivos do seu projeto, que podem ser códigos, imagens, áudios, vídeos ou qualquer coisa relacionada a esse projeto.
  
## Commits

  Um commit é um conjunto de alterações que você fez em um projeto. Ele marca uma versão do seu código. Um commit guarda as alterações feitas nos arquivos, quem fez essas alterações e uma mensagem que resume essa alteração.
  Além disso, cada commit tem um hash único SHA1 que pode ser usado para acompanhar todas as alterações feitas no passado e inclusive pode ser usado para voltar em alguma alteração específica ou em algum ponto no tempo específico do seu código.
  
## Branches

  Branch significa “ramo”, ou seja, uma ramificação do seu código. Imagine a seguinte situação: você tem o seu código que já está funcionando em produção e precisa desenvolver uma nova funcionalidade. Mas você não pode mexer direto no código em produção.
  Para isso, você cria uma ramificação do seu código, uma branch, em que você pega o estado atual daquele código e cria um novo ambiente para desenvolver a nova feature a partir dali.
  Dessa forma, você não altera a versão principal do seu código, consegue desenvolver sua funcionalidade com segurança, e quando esse código estiver funcionando, você poderá colocar ele na principal (merge).
  
 ![branch](https://github.com/cwtshh/aula-github/assets/101185927/9f7c746c-9720-4a15-9376-b12eb10fcee3)


# Como funciona um repositório e como fazer commit
  Quando estamos trabalhando em um repositório, temos três diferentes tipos de zonas virtuais:
  
   * Working Directory
   * Staging Area
   * Commit Area

  O **Working Directory**, também conhecido como Working Tree, é a área em que você está trabalhando. Onde estão todos os seus arquivos, onde você criará, deletará e editará arquivos novos ou velhos. Também é onde estão os arquivos untracked.
  
  Após as alterações, o proximo passo é adicionar essas alterações a **Stagind area**, que age como uma especie de "prévia do commit", mostrando todos os arquivos que foram alterados.
  
  O próximo passo é pegar todas as alterações e fazer um commit com elas. Quando você faz isso, esse commit vai para **commit area** ou também conhecida como local repository. Aqui fica tudo do seu repositório.
  
  Entao nossa ordem fica assim:
   

# Comandos importantes!

``` 
git clone <url>
git branch <nome-da-branch>
git checkout <nome-da-branch>
git status 
git add <arquivo> 
git commit -m "mensagem de commit" 
git push <repositorio-remoto> <nome-da-branch> 
git pull
git revert
git merge <nome-da-branch-com-o-recurso> 
```

# Como criar um repositório?

...

# Como conectar o nosso projeto ao repositório?

...

# Lista de comandos
![Git cheat sheet light (FINAL) (2)](https://github.com/cwtshh/aula-github/assets/101185927/1337d23b-caa9-4222-b7ab-216902e51c7c)
    
