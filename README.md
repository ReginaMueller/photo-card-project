# Photocard Project

Der Website-Layout sollte basierend auf Screenshots und Videos nachgebaut werden.

![image](https://github.com/FlausenImKopf/photo-card-nachbau-mit-sandra/assets/88251068/72b1a254-783c-49bf-a834-b2f328bbcb0a)

## Vorgebenen HTML Start Code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Photo Card</title>
    <link
      rel="stylesheet"
      href="https://unpkg.com/modern-normalize@latest/modern-normalize.css"
    />
  </head>
  <body>
    <header>
      <h1>Photo<br />Card</h1>
      <p>
        On this website you can find a card with a random image from
        <a href="https://www.unsplash.com">unsplash</a>. Try to focus on
        creating the main structure of the HTML and CSS first. Then add the
        details bit by bit. If you make good progress, try to add an animated
        hover effect for the little icon in the image. Oh, and this paragraph
        must only be 65 characters wide.
      </p>
    </header>
    <main></main>
  </body>
</html>
```

## Vorgegebener Bild-Link:

https://source.unsplash.com/600x600/?nature

## feature requests:

### 1. Add subtle Transition:

Beim Hovern über die Karte soll sich das Bild etwas vergrößern, das Bild aber innerhalb der Karte bleiben. Der Schatten der Karte soll die Farbe des Seiten-Textes bekommen. Der Stern sollte anfangs ausgegraut sein und erst beim hovern gelb werden.

### 2. Dark Mode:

Fügt über einen prefers-color-scheme: dark Media Query einen Dark Mode hinzu. Nutzt hierfür Custom Properties.Photocard project

### 3. Add a Footer:

Fügt der Website einen dreispaltigen Footer hinzu. Das Footer Design soll Font Awesome Icons enthalten und von der Struktur so aussehen wie der Beispiel Screenshot:
![image](https://github.com/FlausenImKopf/photo-card-nachbau-mit-sandra/assets/88251068/1c67ae51-b303-4f41-aa00-277c10452bcd)

### 4. Create a list view:

Erstelle ein zweites Stylesheet das du ergänzend zum ersten in die index.html Seite einfügst. Update deinen CSS Code im neuen Stylesheet so, dass die Karte als "List View" dargestellt wird:
![image](https://github.com/FlausenImKopf/photo-card-nachbau-mit-sandra/assets/88251068/2836322b-9136-46c1-a73a-3ebb1ba49266)

### 5. Beide Stylesheets in index verlinken

Das List-View Stylesheet soll im Sinne von responsive design via media query eingebettet werden.
