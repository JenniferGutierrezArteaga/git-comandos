---


---

<h1 id="comandos-básicos-de-git">Comandos básicos de Git</h1>
<p><img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" alt="enter image description here"></p>
<ul>
<li>
<p><strong>Git clone</strong></p>
<blockquote>
<p>Sirve para obtener una copia del repositorio del proyecto, como por ejemplo: ```<br>
git clone <a href="https://link-con-nombre-del-repositorio">https://link-con-nombre-del-repositorio</a></p>
</blockquote>
</li>
<li>
<p><strong>Git branch</strong></p>
<blockquote>
<p>Este comando sirve para crear, listar y eliminar ramas. Ejemplos</p>
<ul>
<li>Para <strong>crear</strong> una nueva rama: git branch [nombre-de-la-rama]</li>
<li>Para <strong>enlistar</strong> las ramas: git branch y git branch --list</li>
<li>Para borrar una rama:</li>
<li>Para borrar una rama: git branch -d [nombre de la rama a borrar]</li>
</ul>
</blockquote>
</li>
<li>
<p><strong>Git checkout</strong></p>
<blockquote>
<p>Principalmente es para cambiarse de una rama a otra, aunque también para checar archivos y commits.<br>
git checkout [nombre-de-la-rama]<br>
Para poder crear una rama y cambiarte al mismo tiempo se puede usar: git checkout -b [nombre de la rama]</p>
</blockquote>
</li>
<li>
<p><strong>Git status</strong></p>
<blockquote>
<p>Nos da toda la información necesaria sobre la rama actual como lo es</p>
</blockquote>
<ul>
<li>Si la rama actual esta actualizada</li>
<li>Si hay algo para confirmar, enviar o recibir (pull).</li>
<li>Si hay archivos en preparación (staged), sin preparación(unstaged) o que no están recibiendo seguimiento (untracked)</li>
<li>Si hay archivos creados, modificados o eliminados</li>
</ul>
</li>
<li>
<p><strong>Git add</strong></p>
<blockquote>
<p>Este comando incluye los cambios de los proyectos en el siguiente commit. El punto que se usa es para agregar todos los cambios o incluso se puede agregar uno en especifico.<br>
Ejemplo:<br>
git add . (para agregar todos los cambios)<br>
git add (nombre del archivo en especifico)</p>
</blockquote>
</li>
<li>
<p><strong>Git commit</strong></p>
<blockquote>
<p>es establecer un punto de control en el proceso de desarrollo al cual puedes volver más tarde si es necesario, incluso se puede agregar un mensaje para señalar los cambios, ejemplo<br>
git commit -m “mensaje de confirmación”<br>
Recordar que git commit guarda los cambios en local</p>
</blockquote>
</li>
<li>
<p><strong>Git push</strong></p>
<blockquote>
<p>Este comando ayuda a enviar los cambios al repositorio remoto<br>
git push [nombre-remoto] [nombre-de-tu-rama] o de otro modo git push -u origin [nombre-de-tu-rama]</p>
</blockquote>
</li>
<li>
<p><strong>Git pull</strong></p>
<blockquote>
<p>Se utiliza para recibir actualizaciones del repositorio remoto, una desventaja es que puede traer conflictos que se deban resolver manualmente. git pull [nombre-remoto]</p>
</blockquote>
</li>
<li>
<p><strong>Git revert</strong></p>
<blockquote>
<p>Sirve para revertir los cambios que se han hecho, se utiliza de la siguiente manera<br>
git log–oneline -&gt; para obtener el código de comprobación del commit al que se quiere regresar, entonces se usa git revert (código de comprobación), en la consola que aparecerá solo es cuestión de usar <strong>shift + q</strong> para salir</p>
</blockquote>
</li>
<li>
<p><strong>Git merge</strong></p>
<blockquote>
<p>Se usa cuando el proyecto esta terminado, este comando fusiona cada una de las ramas con la rama principal. Pero es importante recordar que se tiene que estar en la rama especifica que se quiere fusionar. Ejemplo: git merge [nombre de la rama]</p>
</blockquote>
</li>
</ul>

