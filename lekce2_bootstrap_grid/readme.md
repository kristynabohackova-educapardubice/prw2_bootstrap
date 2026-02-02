# Lekce 2 – Grid systém v Bootstrapu

V této lekci se naučíte pracovat s **grid systémem Bootstrapu**, který slouží
k vytváření rozložení webové stránky pomocí řádků a sloupců.

Grid systém je základním stavebním kamenem responzivních webů a umožňuje
snadno přizpůsobit rozložení stránky různým velikostem obrazovky.

---

## 🎯 Cíle lekce

Po absolvování této lekce budete umět:
- vysvětlit, jak funguje grid systém Bootstrapu,
- používat strukturu `container → row → col`,
- rozdělit stránku na sloupce pomocí tříd `col-*`,
- vytvořit jednoduché responzivní rozložení.

---

## 🧱 Základní princip gridu

Grid systém Bootstrapu je založen na:
- **řádcích** (`row`),
- **sloupcích** (`col`),
- rozdělení jednoho řádku na **12 sloupců**.

Základní struktura vždy vypadá takto:

```html
<div class="container">
  <div class="row">
    <div class="col">Obsah</div>
  </div>
</div>
```

📌 Sloupce (`col`) musí být **vždy uvnitř `row`**.

---

## 📐 Sloupce a jejich šířka

Šířku sloupce lze určit pomocí tříd `col-1` až `col-12`.

Příklad rozdělení řádku na dvě části:

```html
<div class="row">
  <div class="col-8">Hlavní obsah</div>
  <div class="col-4">Postranní panel</div>
</div>
```

Součet šířek sloupců v jednom řádku by měl být maximálně **12**.

---

## 📱 Responzivní chování

Bootstrap umožňuje měnit rozložení podle šířky obrazovky pomocí tzv. **breakpointů**.

Nejčastější třídy:
- `col-12` – výchozí (mobil),
- `col-md-6` – od velikosti *md* polovina řádku,
- `col-lg-4` – od velikosti *lg* třetina řádku.

Ukázka:

```html
<div class="col-12 col-md-6 col-lg-4">
  Responzivní sloupec
</div>
```

Význam:
- mobil → celý řádek,
- tablet → polovina,
- počítač → třetina.

---

## 🧪 Ukázka jednoduchého rozložení

```html
<div class="container py-4">
  <div class="row">
    <div class="col-12 col-md-8">
      <p>Hlavní obsah stránky</p>
    </div>
    <div class="col-12 col-md-4">
      <p>Postranní panel</p>
    </div>
  </div>
</div>
```

---

## 📝 Cvičení

Cvičení k této lekci najdete ve složce **`cviceni/`**.

Každé cvičení má:
- vlastní podsložku (`2.1`, `2.2`, …),
- řešení ve formě HTML souboru.

Postupujte postupně od cvičení **2.1**.
