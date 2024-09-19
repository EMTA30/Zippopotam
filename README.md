# Automatización de API de Zippopotam.us

Este proyecto contiene un script en Python para consultar la API de Zippopotam.us y obtener información sobre un código postal. El script utiliza la biblioteca `requests` para realizar la solicitud HTTP y procesar la respuesta.

## Descripción del Código

El script realiza las siguientes tareas:

1. **Importación de Bibliotecas:**
   - Importa la biblioteca `requests` para hacer solicitudes HTTP.

2. **Función `get_location_info`:**
   - Define una función que toma el código postal y el código del país como parámetros.
   - Construye la URL de la API usando los parámetros proporcionados.
   - Realiza una solicitud GET a la API.
   - Verifica si la solicitud fue exitosa (código de estado 200). Si es así, convierte la respuesta a formato JSON y extrae la información relevante.
   - Imprime la información extraída en la consola.

3. **Ejemplo de Uso:**
   - Pide al usuario que ingrese un código postal y un código de país.
   - Llama a la función `get_location_info` para mostrar la información.

## Requisitos

- Python 3.x
- Biblioteca `requests`

## Instalación

Para instalar las dependencias, asegúrate de tener `requests` instalado. Puedes instalarlo usando pip:

```bash
pip install requests
