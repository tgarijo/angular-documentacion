# Angular cli una guia de consulta

Esta guia es una traduccion en Español del sitio de angular.dev.
Lo que trata esta guia es de resumir y proveer  a los usuarios de una guia rapida de comandos angular-cli
de angular-cli que puedan utilizar

## Instalacion de Angular Cli

#### Con permisos de administración
~~~
npm install -g @angular/cli
~~~

#### Sin permissos de administrador
~~~
sudo npm install -g @angular/cli 
~~~

#### Creacion de un nuevo espacio de trabajo o proyecto
~~~
ng new my-app
~~~

#### Ejecucion de aplicacion
~~~
ng serve --open
~~~
El comando ng server compila y lanza un servidor de aplicaciones ubicado en  http://localhost:4200/
El flag --open (-o) abrira el navegador por defecto en http://localhost:4200/

### Creacion de componentes
Podemos crear componentes, directivas, pipes servicios con ng generate
~~~
ng generate component <nombre>
~~~

### Ejecucion de test
~~~
ng test
~~~

### Despliegue de aplicacion
~~~
ng deploy
~~~
