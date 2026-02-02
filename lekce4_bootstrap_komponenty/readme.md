# Lekce 4 – Základní komponenty Bootstrapu

V této lekci se seznámíte se základními **komponentami Bootstrapu**. Komponenty jsou hotové části uživatelského rozhraní (UI), které se skládají z HTML struktury a Bootstrap tříd.

V praxi to znamená, že si můžete rychle vytvořit např. upozornění, karty nebo odznaky bez psaní vlastního CSS.

---

## 🎯 Cíle lekce

Po absolvování této lekce budete umět:
- vysvětlit, co jsou komponenty a proč se používají,
- vytvořit a upravit upozornění (alert),
- použít odznak (badge),
- vytvořit kartu (card),
- použít skupinu tlačítek (button group).

---

## ⚠️ Alert – upozornění

Komponenta **alert** slouží k zobrazení důležité zprávy.

Základ:

```html
<div class="alert alert-success">
  Operace proběhla úspěšně.
</div>
```

Varianty:
- `alert-primary`, `alert-success`, `alert-warning`, `alert-danger` …

---

## 🏷️ Badge – odznak

**Badge** je malý prvek pro zvýraznění krátké informace (např. „Nové“, počet zpráv).

```html
<span class="badge bg-primary">Nové</span>
<span class="badge bg-danger">5</span>
```

---

## 🃏 Card – karta

**Card** je univerzální komponenta pro obsah (text, odkazy, tlačítka).

```html
<div class="card">
  <div class="card-body">
    <h5 class="card-title">Název</h5>
    <p class="card-text">Text karty</p>
  </div>
</div>
```

---

## 🔘 Button group – skupina tlačítek

Button group umožňuje sdružit více tlačítek vedle sebe.

```html
<div class="btn-group">
  <button class="btn btn-primary">Ano</button>
  <button class="btn btn-secondary">Ne</button>
</div>
```

---

## 📝 Cvičení

Cvičení k této lekci najdete ve složce **`cviceni/`**.

Každé cvičení má:
- vlastní podsložku (`4.1`, `4.2`, …),
- řešení ve formě HTML souboru.

Postupujte postupně od cvičení **4.1**.

