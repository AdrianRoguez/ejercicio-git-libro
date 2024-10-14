# __Trabajando con log/branch y el HEAD en git__

## Ejercicio 1

```code
git log
commit 26e674563fe66c6be68ab4a9223134592a3491c5 (HEAD -> main, origin/main, origin/HEAD)
Author: adrianroguez <sterbenthereaper@gmail.com>
Date:   Thu Oct 10 17:55:55 2024 +0100

    Initial commit
```

```code
cat capitulos/capitulo1.txt
Git es un sistema de control de versiones ideado por Linus Torvalds.
```

```code
git add .

git commit -m "Añadido capítulo 1."
[main 850c7cf] Añadido capítulo 1.
 2 files changed, 26 insertions(+), 1 deletion(-)
 create mode 100644 capitulos/capitulo1.txt

git log
commit 850c7cfd0ac53be5886c460fdc7f84a0273af053 (HEAD -> main)
Author: AdrianRoguez <adriandam2025@gmail.com>
Date:   Thu Oct 10 18:30:24 2024 +0100

    Añadido capítulo 1.

commit 26e674563fe66c6be68ab4a9223134592a3491c5 (origin/main, origin/HEAD)
Author: adrianroguez <sterbenthereaper@gmail.com>
Date:   Thu Oct 10 17:55:55 2024 +0100

    Initial commit

```

## Ejercicio 2

```code
cat capitulos/capitulo2.txt 
El flujo de trabajo básico con Git consiste en:
 1- Hacer cambios en el repositorio.
 2- Añadir los cambios a la zona de intercambio temporal.
 3- Hacer un commit de los cambios.
```

```code
git add .
```

```code
git commit -m "Añadido capítulo 2"
[main a9c6e13] Añadido capítulo 2
 2 files changed, 45 insertions(+)
 create mode 100644 capitulos/capitulo2.txt
```

```code
git log
commit a9c6e13733c44e3525cd733f33f8c580c48e5379 (HEAD -> main)
Author: AdrianRoguez <adriandam2025@gmail.com>
Date:   Thu Oct 10 18:40:09 2024 +0100

    Añadido capítulo 2

commit 850c7cfd0ac53be5886c460fdc7f84a0273af053
Author: AdrianRoguez <adriandam2025@gmail.com>
Date:   Thu Oct 10 18:30:24 2024 +0100

    Añadido capítulo 1.

commit 26e674563fe66c6be68ab4a9223134592a3491c5 (origin/main, origin/HEAD)
Author: adrianroguez <sterbenthereaper@gmail.com>
Date:   Thu Oct 10 17:55:55 2024 +0100

    Initial commit
```
## Ejercicio 3

```code
cat capitulos/capitulo3.txt 
Git permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera simultanea en ellas.
```

```code
git add .
```

```code
git commit -m "Añadido capítulo 3"
[main 2492158] Añadido capítulo 3
 2 files changed, 31 insertions(+)
 create mode 100644 capitulos/capitulo3.txt
adrianssd@adrianssd:~/Descargas/ejercicio-git-libro$ git log
commit 249215813daf01873e368a37c7915a720ecbd8c8 (HEAD -> main)
Author: AdrianRoguez <adriandam2025@gmail.com>
Date:   Sun Oct 13 00:09:58 2024 +0100

    Añadido capítulo 3

commit a9c6e13733c44e3525cd733f33f8c580c48e5379
Author: AdrianRoguez <adriandam2025@gmail.com>
Date:   Thu Oct 10 18:40:09 2024 +0100

    Añadido capítulo 2

commit 850c7cfd0ac53be5886c460fdc7f84a0273af053
Author: AdrianRoguez <adriandam2025@gmail.com>
Date:   Thu Oct 10 18:30:24 2024 +0100

    Añadido capítulo 1.

commit 26e674563fe66c6be68ab4a9223134592a3491c5 (origin/main, origin/HEAD)
Author: adrianroguez <sterbenthereaper@gmail.com>
Date:   Thu Oct 10 17:55:55 2024 +0100

    Initial commit
```

## Ejercicio 4

```code
cat capitulos/índice.txt 
Indice de los cápitulos, con conceptos avanzados de git
```

```code
git add .
```

```code
git commit -m "Se crea el indice."
[main 60dd9ad] Se crea el indice.
 2 files changed, 67 insertions(+)
 create mode 100644 "capitulos/\303\255ndice.txt"
```

```code
git annotate índice.txt
60dd9adc        (AdrianRoguez   2024-10-13 00:19:57 +0100       1)Indice de los cápitulos, con conceptos avanzados de git
```

## Ejercicio 5

```code
git branch bibliografia
```

```code
git branch -av
  bibliografia        e2c45b5 Añadido el índice
* main                e2c45b5 [adelante 1] Añadido el índice
  remotes/origin/HEAD -> origin/main
  remotes/origin/main 60dd9ad Se crea el indice.
```

## Ejercicio 6

```code
cat capitulos/capitulo4.txt 
En este capítulo veremos cómo usar GitHub para alojar repositorios en remoto.
```

```code

```

```code

```

```code

```

```code

```

```code

```

```code

```

```code

```

```code

```

```code

```

```code

```