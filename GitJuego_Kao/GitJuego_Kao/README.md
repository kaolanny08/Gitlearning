# Comandos en gitlearnbranch
##### Name: Kaolanny Rufino Morel
##### Matricula: Kaolanny Rufino Morel
<br>

#### Comando commit
    git commit

#### Comando branch
    git branch bugFix

#### Comando checkout
    git checkout bugFix

#### Comando merge
    git checkout -b bugFix
    git commit
    git checkout main
    git commit
    git merge bugFix

#### Comando rebase
    git branch bugfix
    git checkout bugfix
    git commit
    git checkout main
    git commit
    git checkout bugfix
    git rebase main

#### Comando para referencias relativas
    git checkout C4^

#### Uso del operador ~
    git branch -f main C6
    git branch -f bugfix C0
    git checkout C1

#### Comando para revertir cambios
    git reset local~1
    git checkout pushed
    git revert pushed

#### Comando cherry-pick
    git cherry-pick C3 C4 C7

#### Comando rebase interactivo
    git rebase -i main~4 --aboveAll

#### Comando tag
    git tag v0 C1
    git tag v1 C2
    git checkout C2

![Imagen #1 - juego completo](/Captura.PNG)
![Imagen #2 - juego completo](/Captura2.PNG)