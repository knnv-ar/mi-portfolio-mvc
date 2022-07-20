# Estructura base para proyectos MVC

Recordar que debemos:

1. Clonar el repositorio de Github.
2. Instalar todos los módulos declarados en el archivo `package.json` con el siguiente comando: `npm i` (`i` es un flag que representa un alias de `install`).
3. Sólo para recordar, si vamos a armar a mano los archivos clave se sugiere un orden preestablecido a saber:
   1. /controllers/mainController.js
   2. /routers/main.js
   3. /app.js
4. Para correr el servidor utilizar el comando `npm run dev`. El achivo `app.js` está configurado para que pueda see ejecutado desde un servidor externo que designe un número de puerto específico distinto al 3000. Se puede probar esta funcionalidad con el siguiente comando, suponiendo que queremos correrlo desde el puerto 4444: `PORT=4444 node app.js`