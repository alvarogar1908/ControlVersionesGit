# 3. Lenguaje de marcas: Markdown

## ¿Qué es Markdown?

Markdown es un lenguaje de marcado que facilita dar formato a un texto empleando caracteres de una forma especial. Fue creado por John Gruber en 2004 y nació como una herramienta para convertir texto plano a HTML.

Su finalidad es permitir crear contenido de forma sencilla y mantener un texto legible incluso cuando no se muestra con formato.

## Sintaxis básica

### Títulos

```markdown
# Título principal
## Título de segundo nivel
### Título de tercer nivel
```

### Negrita y cursiva

```markdown
**Texto en negrita**
*Texto en cursiva*
```

### Listas

```markdown
- Primer elemento
- Segundo elemento

1. Primer paso
2. Segundo paso
```

### Enlaces

```markdown
[Documentación de GitHub](https://docs.github.com/es)
```

### Imágenes

```markdown
![Descripción de la imagen](img/ejemplo.png)
```

En GitHub también puede utilizarse HTML básico dentro de Markdown para ajustar el tamaño de una imagen:

```html
<img src="img/ejemplo.png" alt="Descripción de la imagen" width="400" height="250" />
```

La imagen debe guardarse en la carpeta `img` y la ruta debe coincidir con su nombre real.

### Bloques de código

Se pueden mostrar comandos o ejemplos de código usando tres acentos graves antes y después del bloque:

```bash
git status
git add archivo.md
git commit -m "Actualiza documentación"
```

## Editores de Markdown

En la Unidad 2 se mencionan varios editores: MarkdownPad, UberWriter, Visual Studio Code, Typora, Dillinger y StackEdit.io. En los apuntes se indica que la práctica se centrará en Visual Studio Code.

Visual Studio Code es un editor multiplataforma que dispone de extensiones, vista previa e integración con Git.
