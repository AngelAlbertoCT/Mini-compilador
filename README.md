# Compilador Python

Este es un compilador simple escrito en Python. El compilador puede realizar varias tareas, incluyendo la eliminación de comentarios, separación de tokens, validación de variables, conversión de expresiones infix a postfix y generación de código intermedio.

## Funcionalidades

### Eliminación de Comentarios
El código incluye una función `quita_comentarios` que elimina los comentarios de un archivo de entrada y guarda el resultado en otro archivo.

### Separación de Tokens
La función `separa_tokens2` divide el código en tokens individuales, lo que facilita su procesamiento posterior.

### Validación de Variables
La función `verifica_declara_var` verifica la declaración y uso correcto de variables en el código. Si hay errores, devuelve un código de error correspondiente.

### Conversión de Infix a Postfix
El código incluye funciones para convertir expresiones infix a postfix. Esta funcionalidad se utiliza en la generación de código intermedio.

### Generación de Código Intermedio
El compilador puede generar código intermedio a partir de expresiones infix. El código intermedio se produce en forma de instrucciones sencillas que pueden ser utilizadas para generar código ejecutable posteriormente.

## Uso
Para utilizar el compilador, simplemente ejecuta el archivo principal y proporciona el archivo de entrada como argumento. El compilador realizará las tareas especificadas y mostrará el resultado en la consola.

## Ejemplo de Uso
```python
python compilador.py archivo_entrada.txt
```

---

Si necesitas incluir más detalles sobre cómo usar el compilador o alguna otra información específica, no dudes en agregarla.
