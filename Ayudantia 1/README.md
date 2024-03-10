# Ayudantías Cálculo I

Respecto a las versiones con y sin soluciones, veremos que al principio de `main.tex` se encuentran las líneas:

```
\includecomment{soluciones}
\excludecomment{soluciones}
```

Para la versión con solo enunciados, dejamos la línea `\excludecomments{soluciones}` y comentamos la línea `\includecomments{soluciones}`. En caso de querer la versión con enunciados y soluciones, hacemos el proceso inverso, dejamos la línea `\includecomments{soluciones}` y comentamos la línea `\excludecommets{soluciones}`.

Con lo anterior, cada vez que queramos escribir la solución a un ejercicio debemos colocara en un bloque `soluciones`, por ejemplo:

```
\begin{soluciones}
Soy una solución :D
\end{soluciones}
```
