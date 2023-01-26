# task01-grupo13

# Git rebase
É utilizado para alterar um ou vários commit e também é possível unificar diversos commits em um único commit.


![image](https://user-images.githubusercontent.com/73563601/214727711-8afba25a-a1be-43f9-a2d4-262353cbfa00.png)
## Sintaxe
```shell
$ git rebase (nome-da-branch)
```
## Aplicação
```shell
$ git rebase main
```

# Git cherry-pick
Permite ao usuário selecionar commits específicos para trazer ao branch desejado.


![image](https://user-images.githubusercontent.com/73563601/214729395-fe12193e-3559-4763-a188-31ab681d0d1b.png)
## Sintaxe
```shell
$ git cherry-pick (nome-da-branch)
```
## Aplicação
```shell
$ git cherry-pick master
```

# Git revert
É usado para desfazer alterações ao histórico de commits do repositório.


![image](https://user-images.githubusercontent.com/73563601/214730557-d6989c6c-3333-467c-9b6b-406e9a5a97ce.png)

## Sintaxe
```shell
$ git revert 
```
## Aplicação 
```shell
$ git revert HEAD~3
```

# Git squash
A combinação por squash permite que você combine vários commits no histórico do seu branch em um único commit.


![image](https://user-images.githubusercontent.com/73563601/214730843-62a9bab0-ee16-4187-bf30-83bbf2ef2f78.png)

## Sintaxe
```shell
$ git rebase 
```
## Aplicação 
```shell
$ git revert HEAD
```
