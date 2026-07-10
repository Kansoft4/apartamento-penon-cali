# Apartamento en renta · El Peñón, Cali

Landing page de una sola página para un apartamento de 135 m² en renta directa en El Peñón (Cali, Colombia). Objetivo: que el visitante escriba por WhatsApp.

## Estructura

```
index.html          Todo el código (HTML + CSS + JS en un solo archivo)
assets/img/
  hero.jpg          Foto principal
  og.jpg            Imagen del preview al compartir el link
  full/             Fotos en tamaño grande (galería ampliada)
  thumb/            Miniaturas de la galería
```

Sin dependencias ni build. Se abre directo o se sirve como archivos estáticos.

## Ver en local

```bash
python3 -m http.server 8741
# abrir http://localhost:8741
```

## Antes de publicar

En `index.html`, reemplazar `[DOMINIO-AL-PUBLICAR]` por el dominio real en las etiquetas `og:url` y `og:image` para que el preview de WhatsApp muestre la foto.
