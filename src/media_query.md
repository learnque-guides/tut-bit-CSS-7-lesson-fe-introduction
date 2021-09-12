# Media query (responsive design)

* Media query (`@media`) tai yra CSS3 naujas funkcionalumas leidžiantis taikyti tam tikras CSS taisykles priklausomai nuo ekrano dydžio.
* Media query (`@media`) yra pagrindas norint sukurti tinklapį skirta tiek mobiliesiems, tiek ir paprastiems kompiuteriams

Pagrindinė media-query sintaksė:

---

![Media 1](./image/media1.png)

---

![Media 2](./image/media2.png)

---

![Media 3](./image/media3.png)

---

Pavyzdis:

```css
@media screen and (min-width: 480px) {
    body {
        background-color: lightgreen;
    }
}
```

Kai naudojamas media ir bendrai rekomenduojama i `head` pridėti tokia eilutę:

```html
<meta name="viewport" content="width=device-width, initial-scale=1" />
```

tam, kad atidarant tinklapį nebūtų galimybės daryti "zoom" (priartinimo).

Daugiau informacijos:

[https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)