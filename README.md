# Función para Formatear Texto en Archivo de Python

## Descripción
Este repositorio contiene una implementación en Python de una función para formatear texto en un archivo de texto. La función lee un archivo de texto existente, aplica un formato de línea específico según un ancho máximo dado, y sobrescribe el contenido original del archivo con el texto formateado.

## Funcionalidad
La función principal main() realiza las siguientes acciones:

1. Entrada de Usuario:
   - Solicita al usuario ingresar la ruta al archivo de texto existente y el ancho máximo para el formato de línea.

2. Lectura del Archivo:
   - Lee el contenido del archivo especificado.

3. Formateo de Texto:
   - Aplica un formato de línea adecuado al texto utilizando la función format_text().

4. Actualización del Archivo:
   - Sobrescribe completamente el contenido del archivo original con el texto formateado utilizando la función update_text_file().

## Restricciones
El archivo no debe tener más de 1000 caracteres y el ancho máximo no debe superar 100, de lo contrario devuelve un mensaje indicando el error

## Ejemplo
Supongamos que tenemos un archivo de texto ejemplo.txt con el siguiente contenido:

Este es un ejemplo de texto sin formato que será formateado por el script.

Al ejecutas el script el4203_c2.py e ingresas la ruta del archivo ejemplo.txt y 20 como el ancho máximo, el archivo se actualizará para que el texto esté formateado correctamente en líneas de hasta 20 caracteres de ancho.


## Autor:
Fernando Soto Naranjo

