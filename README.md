# Instrucciones para editar el tema

## Prerequisitos

1. Node.js
2. ghost
3. Situarse en la carpeta del tema `cd ./content/themes/hyperspace`.
4. Ejecutar `npm install`


## Comandos para desarrollo local

0. En la raíz del proyecto ejecutar `ghost start`
1. Situarse en la carpeta del tema `cd ./content/themes/hyperspace`
2. Ejecutar `nodemon ../../../current/index.js --watch ./ --ext hbs,js,scss -x "npm run sass"` para compilar los cambios hechas en las hojas de estilo sass.
3. Podrá ver el proyecto en localhost: http://localhost:2368/

**NOTA:** Con cualquier cambio tendrá que actualizar la página manualmente
