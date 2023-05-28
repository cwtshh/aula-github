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
    
