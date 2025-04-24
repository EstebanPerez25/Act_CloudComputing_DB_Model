# Act_CloudComputing_DB_Model
Creación de base de datos en la nube y despliegue de modelo de regresión.

**Equipo:** Idememes

### Integrantes
* Esteban Ángel Pérez Mauraira
* Javier Hernández Arellano
* Leonardo Laureles Olmedo
* Bernardo de Jesús Ortiz Rodriguez
* Itzel Yacquelin Beltrán Reyes

### Instrucciones para correr la API

1. Descargar archivos: requirements.txt, testAPI.csv, api.ipynb
2. Crear archivo json llamado: uri.json, el cual contendrá la uri compartida por canvas.
3. Instalar dependencias de requirements.txt
4. Correr archivo api.ipynb

### Reporte de resultados


Utilizamos la técnica de one hot encoding solamente para la variable 'Title' y transformamos los datos de fecha a números dependiendo de la fecha (la fecha más antigüa será un 0 e irá aumentando conforme pasen los días).
  

Luego, entrenamos un modelo de regresión para predecir la variable de fecha (ya convertida a números enteros) con base en las variables producidas por one hot encoding. Obtuvimos resultados muy malos.


Finalmente, desplegamos el modelo, creando un grypo de recursos en azure y subendo nuestro modelo. Luego lo utilizamos a través de una API.
