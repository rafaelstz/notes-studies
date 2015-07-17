# Configurações inicial do git

## Definindo nome e email

```sh
      git-config --global user.name "name"
      git-config --global user.email "email"
```

#### Verificando a suas configurações
 
```sh
    cat ~/.gitconfig
```

## Iniciando o Git

```sh
    git init
```

## Colocando arquivos no índice

```sh
    git status
```

## Removendo arquivos do ínice

```sh
    git rm --chached file
    git checkout 
```

## Adicionar arquivo no índice

```sh
    git add .
```

> - -i
> - -f
> - *.extensão

## Criando um commit 

```sh
git commit 
```
>  - -m "comment",--amend,-a

## Destruindo commits

```sh
git reset HEAD
```

> - ~1
> - --hard
> - --soft

## Visualizar todos commit

```sh
    git log 
```

> - --stat
> - --reflog
> - --graph

## Guardar arquivos

```sh
git stash
```

>	- list
>	- apply
>	- apply 
>   -  pop
>   -  drop 
>   -  save 
	
## Trabalhando com Branch

```sh
    git branch
    git checkout 
    git checkout -b
```
```sh
    git merge
```
> - --squase
> 

```sh
git rebase
```

> - --continue

```sh
    git branch -d
```
	
