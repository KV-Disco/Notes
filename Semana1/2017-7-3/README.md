# NOTAS

## Description

Notas de las clases y lenguajes.

## Links que nos ha dado Juanma

- Presentacion de Juanma del [Bootcamp Julio 2017](https://skylabcoders.github.io/bootcamp-julio2017/?full#MainCover)
- Ifnformacion basica del [Git](https://www.git-tower.com/learn/git/ebook/en/command-line/basics/getting-ready#chapter)
- [Project Showcase](https://github.com/explore)
- [Prueba del GitHub](https://try.github.io/levels/1/challenges/1)

## Markdown

This *project* is a **demo** of how to write a text with ***markdown***

Done in [Skylab Coders](http://www.skylabcoders.com/en)

Esto es una imagen:
![img](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/KW_2_Pyshma.jpg/300px-KW_2_Pyshma.jpg)

Lista: Con guion "-" se hace una lista y al darle al tabulador se crean sublistas.

- Item 1
- Item 2
- Item 3
    + Sub ietm 1
    + Sub item 2
    + Sub item 3
        * You got the idea

##Comandos de sublime:

```
ctrl+shift+p //
ctrl+p //buscar archivos y funciones.
ctrl+d //multiseleccion de una palabra.
```

##Texto a modo codigo

The functio `sum` will return the sum of 2 numbers
```
function sum(a,b){
    return a+b;
}

sum(3,4)//7
```

##Comandos para terminal

```
ls  // ver los archivos de la carpeta
ls -la  // ver informacion especifica de los archivos de la carpeta
cd  // ir a una carpeta 
cd ..   // Subir una carpeta
pwd     // donde estoy?
rm  // remove
rm -rf  // forse remove
rm -rf .git     // eliminar repositorio git
mkdir   // Crear carpeta nueva

```

##Git

It lets you save a snapshot of your complete project at any time you want.

[Git Cheat Sheet](http://files.zeroturnaround.com/pdf/zt_git_cheat_sheet.pdf)
```
git init    // crear un repositorio git
git status  // muestra si hay un repositorio git
git add <fileName>    // Mete un file especifico en el "staging area".
git add --all   // Mete todos los files en el "staging area".
git add '*.<fileType>'    // Mete todos los files de un tipo (.txt; .jpg; .js)
                          en el "staging area".
git reset <fileName> // sacar un file del "staging area".
git comitt -m "<comentario>" // Mete los files en el repositorio y le da un    
                                nombre al actual estado del proyecto.
git checkout -- <target> // Para devolver un file al stado del antiguo commit.
git branch <brach name> // Copia del codigo para trabajar sobre ella que
                           luego se puede unir al original.
git checkout <brach name> // Cambiar de branchs.
git branch -d <branch name> // Borra un branch.
git log     // Informa de cuantas modificaciones se le han echo al repositorio 
               y quien las ha echo
git log --stat  // Informa de cuantas modificaciones se le han echo al 
                repositorio, quien las ha echo y que modificaciones se han echo.
git diff    //
git remote origin 
git remote -v   //
git clone   //
git push origin master //
```

## JavaScript


### AND Operator

true && true      → true
true && false     → false
false && true     → false
false && false    → false

### OR Operator

true || true      → true
true || false     → true
false || true     → true
false || false    → false

### Functions

```
function sum(a,b){
    return a+b;
}

sum(2,5,6,8,52,4) //2+5= 7
sum(2) //2+undefined= NaN
sum(2,6) //2+6= 8
```

-**Crear una Function** 
```
function sum(a,b){
    return a+b;
}
//or
var sum = function(a,b){ return a+b; };
```


buscar hoisting javascript.