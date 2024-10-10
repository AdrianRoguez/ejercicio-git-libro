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

```

```code

```

```code

```

```code

```