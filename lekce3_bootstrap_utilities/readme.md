# Lekce 3 – Utility třídy v Bootstrapu

V této lekci se naučíte používat **utility třídy** v Bootstrapu. Utility třídy jsou krátké třídy, které nastavují jednu konkrétní vlastnost (odsazení, barvu, zarovnání apod.). Díky nim často není potřeba psát vlastní CSS.

---

## 🎯 Cíle lekce

Po absolvování této lekce budete umět:
- vysvětlit, co jsou utility třídy a proč se používají,
- nastavit odsazení pomocí `m-*` (margin) a `p-*` (padding),
- měnit barvy pomocí `text-*` a `bg-*`,
- zarovnat text pomocí `text-start / text-center / text-end`,
- kombinovat více utility tříd v jednom prvku.

---

## 🧰 Co jsou utility třídy

Utility třídy jsou „rychlé“ třídy, které řeší jednu vlastnost a dají se dobře kombinovat.

Příklady:
- `p-3` – vnitřní odsazení
- `mt-4` – horní okraj
- `text-center` – text na střed
- `bg-light` – světlé pozadí

---

## 📏 Odsazení: margin a padding

Bootstrap používá zkratky:
- `m` – margin (vnější odsazení)
- `p` – padding (vnitřní odsazení)

Směr:
- `t` (top), `b` (bottom)
- `s` (start), `e` (end)
- `x` (vodorovně), `y` (svisle)

Velikost: `0` až `5`

Ukázky:

```html
<div class="p-3">Vnitřní odsazení</div>
<div class="mt-4">Horní okraj</div>
<div class="mx-2">Vodorovné okraje</div>
```

---

## 🎨 Barvy textu a pozadí

Text:
- `text-primary`, `text-success`, `text-danger`, `text-muted`

Pozadí:
- `bg-light`, `bg-dark`, `bg-primary`, `bg-warning` …

Ukázka:

```html
<p class="text-success">Úspěšná zpráva</p>
<div class="bg-light p-3">Světlé pozadí</div>
```

---

## ↔️ Zarovnání a zobrazení

Zarovnání textu:
- `text-start`, `text-center`, `text-end`

Ukázka:

```html
<p class="text-center">Text na střed</p>
```

---

## 📝 Cvičení

Cvičení k této lekci najdete ve složce **`cviceni/`**.

Každé cvičení má:
- vlastní podsložku (`3.1`, `3.2`, …),
- řešení ve formě HTML souboru.

Postupujte postupně od cvičení **3.1**.

