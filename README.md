# ADI-API-REST
Implementacion de una Api Rest para gestion de directorios

Oscar Escabias González y Carlos Rodriguez Gómez-Carreño

Crear un entorno virtual y activarlo:

python3 -m venv .venv source .venv/bin/activate

Instalar las dependencias:

pip install -r requeriments.txt

Para lanzar el servidor:

python3 -m dirApiScripts.server

Las diferentes opciones son:

-a, --admin Establece un token de administracion -p, --port Establece un puerto de escucha -l, --listening Establece una direccion de escucha -d, --db Establece la ruta de la base de datos

Para lanzar el cliente de pruebas:

python3 -m dirApiScripts.client
