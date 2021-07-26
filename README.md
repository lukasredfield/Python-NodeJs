# Ejecutar un script de Python desde Node.js

Código que acompaña al video [Ejecutar Python desde Node.js](https://youtu.be/Jp8TJcDjzVM)

## Descripción
Script de Node.js que ejecuta un script de Python.
script_node.js invoca a script_python.py como un subproceso utilizando la función spawn.
Se establece una comunicación mediante stdin/stdout donde script_node.js envía un texto simple a script_python.py

## Pre-requisitos
* Python 3 instalado
* Node.js instalado

## Ejecución de scripts

Para ejecutar el script de Python de forma independiente, usar en línea de comandos:
```python script_python.py```
La línea de comandos esperará que se ingrese un nombre y se presione la tecla enter, con lo cual generará un saludo.

Para ejecutar el script de Node.js que ejecuta el script de Python, usar en línea de comandos:
```node script_node.js```
El script de Node.js ya tiene un nombre incluido que enviará al script de Python, por lo que mostrará inmediatamente la respuesta enviada por Python.