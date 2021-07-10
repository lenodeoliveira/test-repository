## REPOSITÓRIO DE TESTES E ESTUDOS SOBRE GIT :open_file_folder: 🚀


- Git Branching
    * Criando uma nova branch 
        > `git branch testing`
    * Criando branch e trocando para ela
        > `git checkout -b testing`
    * Trocando de branch
        > `git checkout testing`
    * Obtendo lista de branches
        > `git branch`
    * Verificando o último commit em cada branch
        > `git branch -v`  
    * Histórico de commits mostrando ponteiros de branch
        > `git log --oneline --decorate --graph --all`

- Git branches e mesclagem básica
   * Criando uma branch, trocando para branch principal e executando a mesclagem
      1. `git checkout -b testing` 
      2. `git checkout main`
      3. `git merge testing`
   
   * Após mesclagem podemos deletar a branch
      1. `git branch -d testing`  
   
   * Branches que contém trabalhos que ainda não foram mesclados
      > `git branch --no-merged`




### Autor
---

Lennon de Oliveira
 


 [![Linkedin Badge](https://img.shields.io/badge/-Lennon-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/johnlennondeoliveira/)](https://www.linkedin.com/in/johnlennondeoliveira/) 
