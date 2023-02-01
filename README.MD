#  Cabeceras (c) H1

## Cabeceras H2

### H3 Cabeceras

#### H4 Cabeceras   

##### H5 Cabeceras

###### H6 Cabeceras

# Underlines en markdown

Underline
---------
Underline 2
===========

# Formatos de enfasis 
- la letra *italica* de la primera forma.
- la letra _italica_ de la segunda forma.
- formato __bold__ o **strong** dos maneras.

# Listas Ordenadas y desordenada

1. Lista ordenada 1
2. Lista ordenada 2
3. Lista ordenada 3
- lista desordenada

# Link
- <a href="http://www.google.com">Link en HTML</a>

- [LINK EN MARKDONW](http://www.google.com)
- [link de al index](index.html)
- [link de udemy](https://www.udemy.com/course/introduccion-al-web-responsive-html5-css3/)

# Imagenes

![Logo de Google ](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTIuMB7R6_NKAtZcF6_1Uj29FwB1Nzx718UmQ&usqp=CAU)

# Code snipers

```SQL
CREATE TABLE "topic" (
    "id" integer NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");

-- Initials
insert into "topic" ("forum_id", "subject")
values (2, 'D''artagnian');
```
Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas en MARKDOWN
| NOMBRE | APELLIDO | Documentos |
| ------ | -------- | ---------- |
| Mark   | Burgos   |010302030   |
| Tomas  | Lomas    |008080098   |

# Cita
esto es el texto que va hacer referencia a la cita
> cita muy bonita de ejemplo

Otra referencia de las citas porque quiero crear 2
> Hola Mundo!

# Lineas divisoras
El texto de prueaba de siempre como todos los dias

---
otro ejemplo

***
others bro...
___

# Saltos de linea

lorem ipsum dolor

lorem ipsum dolor sit amet