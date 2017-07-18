# CSS

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <link rel="stylesheet" type="text/css" href="prueva1.css"> //Busca el 
                    // estilo del archivo CSS que se le pase por el link.
    <style type="text/css">                         // Le pone a la pagina
        body { background-color: yellow; }          // el estilo que se escriba
        p { background-color: blue; color: white; } // en eesta parte.
    </style>                                        //
</head>
<body>
    <p style="background-color: black; color: white;">Esto es una prueva para explicar CSS.</p> // Se pone un estylo a este parrafo en especifico.
</body>
</html>
```

Si un archivo tiene varios estilos se aplicara una regla cascada la cual seleccionara el estilo con mas peso, que va desde mas especifico a mas amplio.

En el ejemplo anterior.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <link rel="stylesheet" type="text/css" href="prueva1.css"> // 4º
    <link rel="stylesheet" type="text/css" href="prueva1.css"> // 3º
    <style type="text/css">                         // 
        body { background-color: yellow; }          // 2º => Siguente en la
        p { background-color: blue; color: white; } //   linea de peso.
    </style>                                        //
</head>
<body>
    <p style="background-color: black; color: white;">Esto es una prueva para explicar CSS.</p> // 1º => Es el de mas peso.
</body>
</html>
```

