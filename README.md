# github-ponderada
repositório para avaliação da ponderada de programação (semana 1)


## Introdução
* Essa atividade servirá como relatório do tutorial git/github da semana 1.

* Nele, será mostrado o passo a passo para trabalhar com git e github na prática.

* Os conceitos abordados serão: 
    *  GitHub Get Started
    *  GitHub Edit Code 
    * Pull from GitHub
    * Push to GitHub 
    * GitHub Branch 
    * Pull Branch from GitHub
    * Push Branch to GitHub.
   

## Github Get Started 

* Para começarmos, iremos na conta do github e iniciaremos um novo repositório clicando em "new".

<img src = "./imgs/pg-inical-prog-semana1.png">

## 
* Agora, atribuiremos um nome para o repositório no campo ```Repository name``` e também uma descrição no campo ```Description```

* Atribuiremos o tipo ```Public``` para que todos tenham acesso.

* Por fim, criaremos um README genérico preenchendo a checkbox ```Add a README file``` e clicaremos em ```Create Repository```

<img src ="./imgs/part1-prog-ponderada-1.png">

### Push Local Repository to GitHub

* Para executaremos o push local, primeiro devemos copiar a seguinte url do repositório:

<img src = "./imgs/clone-repo.png">

* Depois disso, colocaremos a url no ```git bash``` específico da pasta onde queremos salvar o acesso

* Em seguida, rodaremos o seguinte comando: ```git remote add origin <url_copiada>```

<img src ="./imgs/origin remote .png">

* Agora, atualizaremos o repositório local através do comando: 
```git pull origin main```

* Por fim, faremos o push na CLI do ```git bash``` por meio desse comando: ```git push --set-upstream origin main```

<img src = "./imgs/push-origin-main .png">

* Finalmente, repositório estará atualizado

<img src = "./imgs/repo-apos-ativ1.png">


## Github Edit Code

* Além de ser uma rede social com repositórios git, o github também possui um editor de código. Para fazer isso no README, basta clicar no lápis da tela inicial

<img src ="./imgs/edit-code-github.png">

* Adiconaremos uma mudança simples no readme e depois commitaremos a mudança no próprio github. 

<img src = "./imgs/commit-nativo-github.png">

## Pull from GitHub

* Para trabalhar em um time de desenvolvimento, é importante que todos os membros da equipe estejam atualizados.

* No git, para trazer as alterações mais recentes do código, você utilizar o ```git pull <remote> <branch>```


* O ```git pull <remote> <branch>``` é a combinação desses dois comandos: ```fetch``` e  ```merge```

* ```fetch``` traz todas as alterações históricas de uma branch/repositório

<img src = "./imgs/fetch.png">

* ```merge``` combina as branchs passadas como parâmetro na linha de comando 

<img src = "./imgs/merge.png">


* Caso você queira somente atualizar o repositório, sem passar por essas etapas, use o  ```git pull <remote> <branch>```

<img src = "./imgs/pull-origin-main.png">

## Push to GitHub

Para fazer o push via git, devemos seguir esses passos:

* fazer alguma alteração

* rodar o comando: ```git commit -a -m "<descrição>"``` 

<img src ="./imgs/git-commit.png">

* Verificar o estado do código com o comando ```git status```


 