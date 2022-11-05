# Ejercicio 1
Se deberá crear un repositorio y realizar una serie de operaciones desde la terminal y responder a las preguntas del cuestionario, en el que se pregunta por comandos utilizados en ciertos pasos.

Los pasos a ejecutar son los siguientes (los pasos en **negrita** indican que hay una pregunta asociada):

1) Crear un repositorio.

2) Crear un archivo `git-nuestro.md` con el contenido:

```
Git nuestro
Git nuestro que estas en los repos
Comprimidos sean tus commits
Venga a nosotros tu log
En el local como en el remote
Danos hoy nuestro pull de cada día
Perdona nuestros conflictos
Como también perdonamos los de otros geeks
No nos dejes caer en detached HEAD
y líbranos de SVN
git commit --amend
```

3) Añadir git-nuestro.md al staging area.

4) Mover lo que hay en el staging area al repositorio.

5) Crear una rama llamada _styled_.

6) Listar las ramas que hay en el repositorio.

7) Moverse a la rama _styled_.

8) Comprobar que se está en la rama correcta.

9) Modificar en el archivo `git-nuestro.md`:

```
*Git* nuestro que estás en los repos
Comprimidos sean tus *commits*
Venga a nosotros tu *log*
En el local como en el *remote*
Danos hoy nuestro *pull* de cada día
Perdona nuestros *conflictos*
Como también perdonamos los de otros geeks
No nos dejes caer en *detached HEAD*
y líbranos de *SVN*
`git commit --amend`
```

10) Añadir los cambios al staging area y luego pasarlos al repositorio.

11) Deshacer el último commit (perdiendo los cambios realizados en el working copy).

12) Rehacer el último commit (el que acabamos de deshacer).

13) Hacer un merge con _master_ (styled absorbe a master).

14) Volver a la rama _master_.

15) Crear una nueva rama llamada _htmlify_.

16) Cambiar a la rama _htmlify_.

17) Modificar en el archivo git-nuestro.md:

```
<p><em>Git</em> nuestro que estas en los repos<br />
Comprimidos sean tus <em>commits</em><br />
Venga a nosotros tu <em>log</em><br />
En el local como en el <em>remote</em><br />
Danos hoy nuestro <em>pull</em> de cada día<br />
Perdona nuestros <em>conflictos</em><br />
Como también perdonamos los de otros geeks<br />
No nos dejes caer en <em>detached HEAD</em><br />
y líbranos de <em>SVN</em><br />
<code>git commit --amend</code></p>
```

18) Hacer un commit.

19) Hacer un merge de _htmlify_ en _styled_ (_styled_ absorbe a _htmlify_).

20) Si hay conflictos, deberemos resolverlos quedándonos con el contenido de la rama _styled_.

21) Desde _master_, hacer un merge con _styled_.

22) Crear una rama _title_ y cambiarse a esa rama.

23) Añadir un título (a tu gusto) al archivo `git-nuestro.md` y hacer un commit.

24) Volver a la rama _master_.

25) Dibujar el diagrama.

26) Hacer un merge “no fast-forward” de _title_ en _master_ (_master_ absorbe a _title_).

27) Deshacer el merge (sin perder los cambios del working copy).

28) Descartar los cambios.

29) Eliminar la rama _title_.

30) Rehacer el merge que hemos deshecho.

31) Volver a master y eliminar el resto de ramas.

32) Volver al commit inicial cuando se creó el poema.

33) Volver al estado final, cuando pusimos título al poema.

34) Crear los siguientes tags:
- **inicial**: en el primer commit.
- **styled**: modificación del paso 10.
- **htmlify**: modificación del paso 17-18.
- **title**: modificación del paso 30.

35) Ir al tag **htmlify**.