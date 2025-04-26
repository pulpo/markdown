## Simplificando la escritura digital con Markdown 

![](https://flisol.info/Logo?action=AttachFile&do=get&target=FLISoL-2015.png)
---

## Contenido de la charla 

1. Origen de Markdown
2. Sintaxis básica de Markdown
3. Aplicaciones prácticas
4. Herramientas útiles
5. Consejos y buenas prácticas
6. Errores comunes
7. Q&A 

---

## 1. Origen de Markdown

---

- **¿Qué es Markdown?**

  - Lenguaje de marcado ligero creado por [John Gruber](https://daringfireball.net/projects/markdown/) en el año 2004.
  - Diseñado para ser simple y legible en texto plano.
  - Inspirado en correo electrónico antiguo y en lenguajes de marcado más complejos.

- **Objetivo principal:**

  - Convertir texto plano en HTML de manera sencilla.
  - Facilitar la escritura y el formato sin necesidad de usar herramientas gráficas.

---

## 2. Sintaxis básica de Markdown

---

### Elementos básicos:

---

#### Encabezados
```markdown
# Título principal (H1)
## Subtítulo (H2)
### Sección (H3)
```

---

Resultado:

# Título principal (H1)
## Subtítulo (H2)
### Sección (H3)

---

#### Listas no ordenadas
```markdown
- Elemento 1
- Elemento 2
  - Subelemento
  - Otro subelemento
```

Resultado:
- Elemento 1
- Elemento 2
  - Subelemento
  - Otro subelemento

---

#### Listas ordenadas
```markdown
1. Primer paso
2. Segundo paso
3. Tercer paso
```

Resultado:
1. Primer paso
2. Segundo paso
3. Tercer paso

---

#### Listas ordenadas
```markdown
1. Primer paso
1. Segundo paso
1. Tercer paso
```

Resultado:
1. Primer paso
1. Segundo paso
1. Tercer paso


---

#### Negrita y cursiva
```markdown
**Texto en negrita**
*Texto en cursiva*
***Texto en negrita y cursiva***
```

Resultado:
**Texto en negrita**
*Texto en cursiva*
***Texto en negrita y cursiva***

---

#### Citas

```markdown
> Este es un texto citado.
> Puedes tener varias líneas.
```

Resultado:
> Este es un texto citado.
> Puedes tener varias líneas.

---

#### Citas

![](img/stallman_sierras_chicas.jpg)
> "La educación es fundamental para garantizar una sociedad libre. 
> Debemos enseñar a las personas sobre los principios y ventajas del software libre."
> 
> -- Richard Stallman --

---

![](https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Richard_Stallman_by_gisleh_01.jpg/300px-Richard_Stallman_by_gisleh_01.jpg)
> Debemos enseñar a las personas sobre los principios y ventajas del software libre.
> 
> -- Richard Stallman --



---

#### Enlaces

```markdown
[texto del enlace](https://url.com)
```

Resultado:

[texto del enlace](https://url.com)

---

#### Imágenes

```markdown
![El Seba en Megatone](https://imgs.xkcd.com/comics/linux_user_at_best_buy.png)
```

Resultado:

![El Seba en Megatone](https://imgs.xkcd.com/comics/linux_user_at_best_buy.png)

---

![Perdón, la tentación es fuerte](https://imgs.xkcd.com/comics/open_source.png)

---

### Código

```markdown
    ```html
    <html>
      <head>
        <title>Flisol Sierras Chicas</title>
      </head>
      <body>
        <h1>Tiene su propio Stallman</h1>
      </body>
    </html>
    ```
```

Resultado:

```html
<html>
  <head>
    <title>Flisol Sierras Chicas</title>
  </head>
  <body>
    <h1>Tiene su propio Stallman</h1>
  </body>
</html>
```


---

### Tablas

```markdown
| Columna 1 | Columna 2 | Columna 3 |
|----------|----------|----------|
| Contenido 1 | Contenido 2 | Contenido 3 |
| Contenido 4 | Contenido 5 | Contenido 6 |
```

Resultado:

| Columna 1 | Columna 2 | Columna 3 |
|----------|----------|----------|
| Contenido 1 | Contenido 2 | Contenido 3 | 
| Contenido 4 | Contenido 5 | Contenido 6 |

---

### Separadores

`---`

Resultado:

Bueno.. si pongo el resultado en esta herramienta me separa una slide :joy:

---

## 3. Aplicaciones prácticas

---

### ¿Para qué usar Markdown?

- **Documentación:** README.md, guías, tutoriales.
- **Correo electrónico:** Enviar textos formateados sin HTML.
- **Sitios web:** Convertir a HTML para blogs o páginas estáticas.
- **GitHub y plataformas similares:**
  - Issues, pull requests, comentarios.
  - Documentación de proyectos.

---

## 4. Herramientas útiles

---

### Editores de Markdown:

1. Cualquiero editor de text sirve.
    1. **vim** (el que te enamora)
    2. **nano** (el minimalista)
    3. **emacs** (el elegido por los jugadores de mortal kombat) 
1. **Visual Studio Code** + extensiones (Markdown Preview).
2. **Typora**: Editor con vista previa integrada. (antes era open)
3. **Obsidian**: Editor de texto potente con muchísimos plugins.
4. [**CodiMD**](https://github.com/hackmdio/codimd): Editor de Markdown, con colaboración en tiempo real. 

---

### Convertidores:

- [**Pandoc**](https://pandoc.org/): Convertir Markdown a PDF, DOCX, HTML, etc.
- **Markdown from LaTeX**: `\usepackage[settings]{markdown}`

---

### Presentaciones:

- [**Reveal.js**](https://revealjs.com/): Presentaciones interactivas con Markdown.
- [**mdp**](https://github.com/visit1985/mdp): Presentaciones desde la terminal
- [**mkslides**](https://github.com/MartenBE/mkslides): Lo que estás viendo ahora

---

### Generadores de sitios

- [**Hugo**](https://gohugo.io/)
- [**Jekyll**](https://jekyllrb.com/)

---

## 5. Consejos y buenas prácticas

1. **Consistencia:**
   - Mantén un formato uniforme en tu documento.
2. **Legibilidad:**
   - Escribe el texto de manera clara y ordenada.
3. **Uso moderado de negrita/cursiva:**
   - **No abuses, usa solo para énfasis. :troll:**
4. **Pruebas:**
   - Revisa cómo se ve tu documento en diferentes herramientas.

---

## 6. Errores comunes

1. **Espaciado incorrecto:**
   ```markdown
   # Título
   Esto está mal
   ```

   En lugar de:
   ```markdown
   # Título

   Esto está bien
   ```

2. **Falta de saltos de línea:**
   - Usa dos espacios al final de la línea o una etiqueta `<br>`.


---

## 7. Cerrando 

- **Markdown es simple pero poderoso.**
- Ideal para documentación técnica y contenido estructurado.
- Aprende los fundamentos y practica con diferentes herramientas.

---

**Gracias por visitarnos**

¿Alguna pregunta?

![Conference Question](https://imgs.xkcd.com/comics/conference_question.png)

---

Los invitamos al grupo de Telegram de [Flisol Sierras Chicas](https://t.me/flisol)

![Flisol Sierras Chicas](img/qr.gif)

Si querés bajar el material de la charla 

![](img/charla.gif)
