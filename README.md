# Guía de Markdown

Markdown es un lenguaje de marcado ligero que te permite formatear texto de manera sencilla y rápida. Es ampliamente utilizado en la escritura de documentos, blogs, READMEs de proyectos en GitHub y en muchas otras aplicaciones. En este documento, aprenderás los conceptos básicos de Markdown.

## Indice
- [Encabezados](#encabezados)
- [Párrafos](#párrafos)
- [Estilos de Texto](#estilos-de-texto)
- [Listas no ordenadas](#listas-no-ordenadas)
- [Listas ordenadas](#listas-ordenadas)
- [Enlaces](#enlaces)
- [Imágenes](#imágenes)
- [Citas](#citas)
- [Codigo](#código)
- [Tablas](#tablas)
- [Lineas horizontales](#líneas-horizontales)
- [Conclusion](#conclusiones)

## Encabezados

Puedes crear encabezados utilizando el símbolo `#`. Cuantos más `#` coloques, más pequeño será el encabezado. Por ejemplo:


# Encabezado 1
## Encabezado 2
### Encabezado 3

## Párrafos
Los párrafos se crean simplemente escribiendo texto. Si deseas crear un nuevo párrafo, simplemente deja una línea en blanco entre ellos.

## Estilos de Texto
Puedes aplicar diferentes estilos de texto de la siguiente manera:

Negrita: **texto en negrita** o __texto en negrita__
Cursiva: *texto en cursiva* o _texto en cursiva_
Negrita y Cursiva: ***negrita y cursiva***
Listas
Markdown admite listas ordenadas y no ordenadas:

## Listas no ordenadas:

- Elemento 1
- Elemento 2
- Elemento 3

## Listas ordenadas:

1. Primer elemento
2. Segundo elemento
3. Tercer elemento

## Enlaces
Puedes crear enlaces de la siguiente manera:

[Texto del enlace](URL)
Por ejemplo:

[OpenAI](https://www.openai.com)

## Imágenes
Insertar imágenes es similar a los enlaces, pero con un signo de exclamación (!) antes:

![Texto alternativo de la imagen](URL de la imagen)

![Ejemplo](data:image/png;base64,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)

## Citas
Puedes citar texto utilizando el símbolo ">" al principio de una línea:

> Esto es una cita.
## Código
Para formatear texto como código, puedes usar comillas simples ` o triples ```. Por ejemplo:

Inline code: codigo_inline

Bloque de código:

```
function ejemplo() {
// Código de ejemplo
}
```

## Tablas
Puedes crear tablas utilizando barras verticales y guiones:


Copy code
| Encabezado 1 | Encabezado 2 |
| ------------- | ------------- |
| Celda 1,1 | Celda 1,2 |
| Celda 2,1 | Celda 2,2 |

## Líneas horizontales
Puedes crear líneas horizontales utilizando tres guiones, tres asteriscos o tres guiones bajos:

```
---
***
___
```

# Conclusiones
Markdown es una herramienta poderosa y simple para formatear texto en documentos web. Esta guía proporciona solo una introducción básica; hay muchas más características y extensiones disponibles. ¡Aprender Markdown es una habilidad valiosa para cualquiera que trabaje con contenido en línea!

Si deseas obtener más información sobre Markdown o aprender sobre sus características avanzadas, puedes consultar la documentación oficial de Markdown.

¡Diviértete escribiendo en Markdown!