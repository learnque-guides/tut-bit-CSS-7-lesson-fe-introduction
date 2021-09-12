# Naujos CSS3 savybės (ang. properties)?

* border-radius - leidžia suapvalinti rėmelius (ang. borders).
* box-shadow - leidžia uždėti šešelius aplink elementą.
* text-shadow - leidžia uždėti šešėlį aplink tekstą.
* opacity - leidžia keist peršvečiamumą (ang. opacity).
* transform - leidžia apsukti ar kitaip transformuoti objektą.
* font-face - leiždia panaudoti ir importuoti šriftą.

<style>
    .interactive {
        background-color: #f4f4f4;
        border: 1px solid #d5d5d5;
        color: #1b1b1b;
        padding: 10px;
        width: 100%;
    }
</style>

<iframe class="interactive" height="390" src="https://interactive-examples.mdn.mozilla.net/pages/css/border-radius.html" title="MDN Web Docs Interactive Example" loading="lazy">
</iframe>

---

<iframe class="interactive" height="390" src="https://interactive-examples.mdn.mozilla.net/pages/css/box-shadow.html" title="MDN Web Docs Interactive Example" loading="lazy">
</iframe>

---

<iframe class="interactive" height="390" src="https://interactive-examples.mdn.mozilla.net/pages/css/text-shadow.html" title="MDN Web Docs Interactive Example" loading="lazy">
</iframe>

---

<iframe class="interactive" height="390" src="https://interactive-examples.mdn.mozilla.net/pages/css/transform.html" title="MDN Web Docs Interactive Example" loading="lazy">
</iframe>

---

```css
@font-face {
  font-family: "Open Sans";
  src: url("/fonts/OpenSans-Regular-webfont.woff2") format("woff2"),
       url("/fonts/OpenSans-Regular-webfont.woff") format("woff");
}
```