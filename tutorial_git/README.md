# Tutorial de manejo de repositorio en Github

## Inicializaci�n
1. Primero instalar la aplicaci�n Desktop de Github. Se descarga [ac�](http://desktop.github.com)
![](./install_1.jpg)
2. Segundo registrarse en Github
![](./github_login_signin.jpg)
3. Ir al repositorio en http://github.com/fifabsas/talleresfifabsas
![](./repo_access.jpg)
4. Forkear el repositorio, es decir hacerse una copia del repositorio en tu cuenta
![](./repo_fork.jpg)
![](./repo_fork_1.jpg)
5. En la aplicaci�n de Github de escritorio, clonar el repositorio reci�n forkeado.
![](./repo_cloning.jpg)

Hecho esto ya est�s listo para trabajar

## Pull requests y branches
Los pull requests permiten que vos trabajes en tu copia del repositorio, y despu�s le pidas al administrador del repositorio padre que adose los cambios que efectuaste vos, en alguna rama o *branches* del repositorio. Nosotros como no tenemos mucha complejidad tenemos solo dos ramas: **master** (donde va todo el c�digo) y **gh-pages** (d�nde va todo lo de la p�gina web). 

Hecho el trabajo en la rama que corresponda (es decir, cambiados los archivos en la carpeta del repositorio), en la aplicaci�n del Github hacemos lo siguiente
1. Commiteamos, es decir subirlo a Github, el trabajo. La regla es commitear seguido, commitear poco y ser descriptivo en lo commiteado.
![](./commit.jpg)
2. Creamos un pull requests y comparamos con la rama del repositorio original padre
![](./pull_requests.jpg)
![](./pull_requests_1.jpg)
![](./pull_requests_2.jpg)
3. Finalmente, en la p�gina del pull requests del repositorio padre se puede comentar detalles de los cambios, hacer seguimiento, y cerrarlo al repositorio padre
![](./pull_resolve.jpg)