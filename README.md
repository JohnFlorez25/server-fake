# Server-fake

Repositorio para explicar la anatomía de una API REST

Para crear nuestra API FAKE vamos a usar el recurso JSON-SERVER, la documentación oficial se encuentra en el siguiente enlace:

https://github.com/typicode/json-server

Una vez que descargue o clone este respositorio debe ubicarse por consola en la ruta del proyecto y realizar los siguientes pasos:

1. Instale de forma global json-server ejecutando por la terminal de comando la siguiente serie de instrucciones `npm install -g json-server`
2. Ejecute la siguiente serie de instrucciones para escuchar por defecto en el puerto 3000 su API FAKE: `json-server --watch db.json`
3. Enjoy :P!

> NOTA: si desea cambiar el puerto por el cual desea levantar su API FAKE ejecute la siguiente serie de instrucciones en la terminal de comandos en el paso 2 `json-server --watch db.json --port 3004` , puede seleccionar su puerto de preferencia alternativo
