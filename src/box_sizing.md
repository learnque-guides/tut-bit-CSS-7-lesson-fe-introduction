# box-sizing

`box-sizing` leidžia nurodyti kaip turėtų būti vykdomas elemento aukščio ir pločio skaičiavimas (koks turėtų būti taikomas algoritmas).

Yra du `box-sizing` variantai:

* **content-box** yra numatytasis (ang. default). Kai mes turime **content-box** tai *padding* ir *border* dydžio (pločio) reikšmės nėra iskaičiuojamas į bendrą elemento plotį ir aukštį. Jei mes elementui nurodysime plotį kaip 100 px, tada elemento "content box" plotis bus 100 px, bet jei mes dar nurodysime *padding* 10px, tai galutinis plotis bus atvaizduotas atsižvelgiant į mūsų nurodytą *padding'a*.
* **border-box** pasako naršyklei atsižvelgti į *padding* ir *border* reikšmes (pločio) ir galutinis elemento plotis, bus toks koki mes nurodome naudojant *width*

<style>
    .interactive {
        background-color: #f4f4f4;
        border: 1px solid #d5d5d5;
        color: #1b1b1b;
        padding: 10px;
        width: 100%;
    }
</style>


<iframe class="interactive" height="390" src="https://interactive-examples.mdn.mozilla.net/pages/css/box-sizing.html" title="MDN Web Docs Interactive Example" loading="lazy">
</iframe>