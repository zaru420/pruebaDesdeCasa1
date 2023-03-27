# pruebaDesdeCasa1
probando a crear repositorios y  configurando el servidor.

# Como ver el gráfico de ramas del repositorio:
https://ardalis.com/git-graph-visualizes-branches-in-vs-code-for-free/

# Comandos GIT
<h2> Comandos útiles</h2>
<p><b>git status</b> para ver el seguimiento de los archivos(untracked files: no esta en seguimiento y esta en rojo)</p>

<h2>Subir últimos cambios</h2>
<p><b>git add .</b> añadir al seguimiento<b>(staging area)</b> todos los archivos, si cambio el . por un archivo o carpeta, hace el seguimiento de ese archivo.</p>
<p><b>git commit -m "titulo del commit" -m "descripcion opcional del commit" </b> el commit es el titulo que le pongo al subirlo local repository</p>
<p><b>git push</b> sube lo del repositorio local al repositorio remoto</p>

<h2> Descargar repositorio remoto</h2>
<p><b>git clone https://github.com/zaru420/Ejercicio-1.git </b> Para descargar el proyecto por primera vez.</p>
<p><b>git pull </b> para descargar los ultimos cambios del repositorio remoto(actualizarlo)</p>

<h2>Trabajar entre ramas</h2>
<p><b>git checkout master</b> para cambiar a la master, cambiar master por otra rama para cambiar de ramas, en el repositorio local.</p>
<p><b>git branch nombreDeLaRama</b> para crear una rama</p>
<p><b>git branch</b> para ver en que rama estas, y cuales hay creadas</p>
<p><b>git log </b> ver los commit que hay en dicha rama(datos de id, autor y fecha)</p>

# Comandos para la terminal
<p><b>cd zonaDeTrabajo</b> para ir a la carpeta que se necesita</p>
<p><b>cd ..</b> para ir hacia atras carpeta por carpeta</p>

<h2> Node </h2>
<p> Instalar node.js (x64) https://nodejs.org/en/download (seguramente reiniciar el PC) </p>
<p> npm --version (desde la terminal.) y si da error: { <br>
        Open Control Panel -> System and Security -> System -> Advanced System Settings -> Environment Variables<br>
        In "User variables" or "System variables" find the variable Path. (If it doesn't exist, create it.)<br>
        Add your node.js folder path at the end of the variable value, beginning with a semicolon separating it from previous values. e.g. ;C:\Program Files\nodejs<br>
        Restart your command prompt.
}  </p>
<p> npm install -g typescript ; ver version instalada de typescript: npm tsc -v ; npm tsc --version</p>
<p> npm install -g @angular/cli ; ver version instalada de angular: npm ng --version </p>

<h2> Pasos para creacion de un proyecto (con node, typescript, jquery):</h2>
<p>1. Crear el proyecto con node.js: npm init </p>
<p>2. Agregar las dependencias de typescript al proyecto: npm install --save-dev typescript </p>
<p>3. Agregar las dependencias de jquery al proyecto:  npm install @types/jquery --save-dev  </p>

<h2> Pasos para creacion de un proyecto ( angular):</h2>
<p>1. Crear el proyecto con angular: ng new my-app ; my-app = el nombre que se le quiere dar al proyecto. </p>
<p>1. Crear el proyecto con angular en un directorio especifico: ng new my-app --directory c:\proyecto_angular </p>
<p>2. Acceder al directorio y arrancar angular:<br>
 cd my-app<br>
 ng serve</p>
 <p>Cambiar de puerto: ng serve --port 80</p>
 <p> iniciar el servidor y abrir el navegador: ng serve --open </p>

 <p> buscar mas informacion de angular sobre: componentes, directivas, pipes(rutas), servicios.<br>
 https://www.youtube.com/watch?v=CitMo3hip6Y&ab_channel=pildorasinformaticas</p>

  <h1>Tecnologías utilizadas en una aplicación web con Spring Boot, Hibernate, TypeScript, Angular y Java
  </h1>
  <h2>Front-end (cliente):
  </h2>
  <ul>
    <li>
      <strong>TypeScript:
      </strong> es un lenguaje de programación que se utiliza para crear aplicaciones web del lado del cliente. TypeScript es un superset de JavaScript y se compila a JavaScript.
    </li>
    <li>
      <strong>Angular:
      </strong> es un framework de JavaScript/TypeScript para crear aplicaciones web del lado del cliente. Angular proporciona una serie de características para facilitar la creación de aplicaciones web, como la creación de componentes, inyección de dependencias, manejo de formularios, enrutamiento y animaciones.
    </li>
  </ul>
  <h2>Back-end (servidor):
  </h2>
  <ul>
    <li>
      <strong>Spring Boot:
      </strong> es un framework de Java que se utiliza para crear aplicaciones web del lado del servidor. Spring Boot proporciona una serie de características para facilitar el desarrollo de aplicaciones web, como la configuración automática, el inicio rápido y la integración con otros frameworks de Spring.
    </li>
    <li>
      <strong>Hibernate:
      </strong> es un framework ORM que se utiliza para interactuar con una base de datos relacional en una aplicación web del lado del servidor. Hibernate mapea automáticamente las clases Java a tablas de base de datos y proporciona una API de objetos para realizar operaciones de base de datos.
    </li>
    <li>
      <strong>Java:
      </strong> es un lenguaje de programación que se utiliza para crear aplicaciones web del lado del servidor. Java es uno de los lenguajes de programación más utilizados para el desarrollo de aplicaciones empresariales.
    </li>
    <li>
      <strong>Base de datos relacional:
      </strong> una base de datos relacional se utiliza para almacenar y recuperar datos en una aplicación web del lado del servidor. Algunas bases de datos relacionales comunes son MySQL, PostgreSQL y Oracle.
    </li>
  </ul>
  <p>Es importante destacar que en un proyecto típico de desarrollo de software, las tecnologías utilizadas pueden variar dependiendo de los requisitos y necesidades del proyecto. Además, las tecnologías mencionadas anteriormente son solo una pequeña parte de las herramientas y tecnologías disponibles para el desarrollo de aplicaciones web.
  </p>
