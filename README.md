# ProyectoFinal

Instrucciones Detalladas para el Software:
Preparar la Base de Datos:

Localiza el archivo de la base de datos "proyecto_final.sql" en tu equipo.
Abre XAMPP y asegúrate de que los servicios de Apache y MySQL estén activos.
Accede a phpMyAdmin desde tu navegador (usualmente en http://localhost/phpmyadmin).
Crea una nueva base de datos con el nombre "proyecto_final".
Importa el archivo "proyecto_final.sql" en la base de datos recién creada. Para ello:
Selecciona la base de datos "proyecto_final".
Haz clic en la pestaña Importar.
Carga el archivo SQL y haz clic en Continuar.
Verifica que las tablas y datos se hayan importado correctamente.



Iniciar el Backend Principal:

Ubica la carpeta donde se encuentra el archivo del backend principal (todo.js).
Ejemplo: C:\ruta\del\proyecto\backend_principal
Abre una terminal o CMD en esa ubicación:
Si estás en Windows, puedes hacerlo haciendo clic derecho en la carpeta y seleccionando Abrir en el terminal o Abrir CMD aquí.
Asegúrate de tener Node.js instalado en tu sistema. Si no lo tienes, descárgalo e instálalo desde nodejs.org.
Ejecuta el siguiente comando para iniciar los servicios del backend:
"node todo.js"
La terminal mostrará un mensaje confirmando que el backend principal se ha iniciado correctamente (por ejemplo, "Servidor corriendo en el puerto 3000").

Iniciar el Backend de Comentarios:
Accede a la carpeta donde se encuentra el archivo del backend de comentarios (mongo.js).
Ejemplo: C:\ruta\del\proyecto\backend_comentarios
Abre una terminal o CMD en esa ubicación.
Ejecuta el siguiente comando para iniciar este servicio:
node mongo.js
Verifica que el servicio de comentarios también esté corriendo correctamente (por ejemplo, "Servidor de comentarios en ejecución en el puerto 4000").

Iniciar el Frontend (Angular):
Navega a la carpeta del proyecto frontend en Angular, llamada "proyectofinal".
Ejemplo: C:\ruta\del\proyecto\proyectofinal
Abre una terminal o CMD en esa ubicación.
Asegúrate de tener Angular CLI instalado en tu sistema. Si no lo tienes, instálalo globalmente con el siguiente comando:
npm install -g @angular/cli
Una vez instalado, ejecuta el siguiente comando para iniciar el frontend:
ng serve -o
Este comando iniciará el servidor de desarrollo y abrirá automáticamente la interfaz gráfica del proyecto en tu navegador predeterminado, en la dirección http://localhost:4200.
