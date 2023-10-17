## Aplicacion de ejemplo para implemetar docker.
Para ejecutar el proyecto debes tener docker instalado
Esta implementación usa un volumen nombrado para que el contenido producido en la base de datos no se pierda.\n
En este proyecto se monta el contenedor definido en el archivo docker-compose-dev.yml, este en particular está implementado en modo de desarrollo para que al hacer cambios en index.js los cambios se implementen automáticamente.
# Ejecución
Ejecuta en la terminal "docker compose -f docker-compose-dev.yml up" \n
Mientras el docker se ejecuta, entra en tu navagador a localhost:3000 para que veas los registros de la base de datos\n
Entra a a "localhost:3000/crear" para hacer un nuevo registro y regresa a "localhost:3000" para ver los registros actuales.
