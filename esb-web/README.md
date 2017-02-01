# esb-prime-webpack
Fully functional web app with webpack and angular integrated with Jquery and bootstrap.

# instruciones para instalar y correr la app en modo desarrollo

1. instalar la ultima version de node.js 
  a. Windows https://nodejs.org/es/ (> v7.0) (unica vez) or 
  b. Linux -> curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -> sudo apt-get install -y nodejs
2. instalar git https://git-scm.com/ (unica vez, ya viene con linux)
3. ejecutar el comando -> npm install (sobre el directorio root de la app)
4. levantar el servidor express-> npm run server (sobre el directorio root de la app)

-- La aplicacion estara disponible en http://localhost:8080 --

# instruciones para instalar y correr la app en modo producion (Linux)

1. instalar la ultima version de node.js -> curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -> sudo apt-get install -y nodejs
2. instalar apache http server -> apt-get install apache2
  a. modificar el archivo /etc/apache2/sites-available -> "DocumentRoot /var/www/(distName)"
3. ejecutar el comando -> npm install para bajar las dependencias (sobre el directorio root de la app)
4. ejecutar el comando ->npm run build para compilar la app (sobre el directorio root de la app)
5. copiar la carpeta con la compilacion al servidor ejecutando el comando -> cp -avr (ruta al proyecto)/dist /var/www/(distName)
4. levantar el servidor apache ejecutar el comando -> /etc/init.d/apache2 start 

-- La aplicacion estara disponible en http://localhost --
