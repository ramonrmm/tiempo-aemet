# Previsión del tiempo con AEMET

Este notebook realiza una consulta a la API de AEMET para obtener la previsión meteorológica de distintas comunidades autónomas.

## Requisitos
Para ejecutar este notebook, necesitas instalar las siguientes bibliotecas:
```bash
pip install requests babel
```

## Tecnologías utilizadas
- **requests**: Para realizar solicitudes a la API de AEMET.
- **IPython.display**: Para mostrar contenido en HTML dentro de Jupyter.
- **datetime**: Para el manejo de fechas.
- **babel.dates**: Para formatear fechas en español.
- **re**: Para trabajar con expresiones regulares.

## Estructura del Notebook
1. **Importación de librerías**: Se cargan los módulos necesarios.
2. **Obtención de URLs**: Se extraen las URLs de consulta de la API de AEMET.
3. **Consulta a la API**: Se realiza una petición HTTP para obtener la información meteorológica.
4. **Procesamiento de datos**: Se formatean las fechas y se extraen los datos relevantes.
5. **Visualización**: Se presentan los resultados de manera estructurada.

## Uso
Abre el notebook en Jupyter y ejecuta las celdas en orden. Asegúrate de tener conexión a Internet para que la consulta a la API funcione correctamente.

## Notas
- Si la API devuelve un error HTTP, verifica que la clave de acceso es válida.
- En caso de problemas de conexión, revisa tu acceso a Internet.

## Autor
Este notebook fue desarrollado Por Ramón Morales para obtener información meteorológica automatizada de AEMET.

