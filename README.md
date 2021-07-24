# Flask app 

## Iniciar una app para usar flask

- Crear directorio raiz.

> $mkdir ~/...

- Iniciar un entorno virtual

> $python3 -m venv venv

- Iniciar el entorno Virtual

> . venv/bin/activate

- Instalar Flask

> $pip3 install Flask

- Para desactivar el entorno virtual se puede usar el siguiente comando

> $deactivate

- Crear el archivo .py

> $touch ******.py

- Dentro del archivo .py para un "hola mundo" simple:

> from flask import Flask
>
> app = Flask(__name__)
> 
> @app.route("/")
>       def hola_mundo():
>               return "<h1>Hola Mundo</h1>"       

- 
