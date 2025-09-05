# RAG

# Embeddings

### Que son?

Son la representación numérica de la información. Por ejemplo, las palabras de un texto pueden ser representadas como vectores en un espacio vectorial en donde las palabras que contienen un significado semántico parecido son posicionadas cerca.

Vectores por palabras y vectores por contexto → no profundizar. 

![image.png](attachment:10f411ea-7c32-4bcd-99ef-71c71bb22e91:image.png)

### Antes de aplicar embedding

- Tokens
    - Que es:
    Es definir cada pedazo del texto en números enteros que luego el modelo de embedding puede usar para generar su base de datos vectorial.
- chunks
    - Cuando tenemos párrafos muy grandes, en vez de dividir por palabra o por subpalabra, se espera dividir en bloques de texto manejables (chunks se hablara mas adelante).

### Almacenamiento en memoria

luego de generar nuestro embedding que son vectores, se deben guardar en bases de datos vectoriales.
