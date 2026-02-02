# Lekce 6 – Formuláře v Bootstrapu

V této lekci se naučíte vytvářet **formuláře pomocí Bootstrapu**. Bootstrap nabízí připravené třídy, díky kterým jsou formuláře přehledné, jednotné a responzivní bez nutnosti psát vlastní CSS.

---

## 🎯 Cíle lekce

Po absolvování této lekce budete umět:
- vytvořit základní formulář,
- použít třídy `form-label`, `form-control` a `form-select`,
- vytvořit checkbox a radio tlačítka,
- správně strukturovat formulář pomocí `mb-*`,
- použít tlačítko pro odeslání formuláře.

---

## 🧱 Základ formuláře

Základní struktura formuláře:

```html
<form>
  <div class="mb-3">
    <label class="form-label">E-mail</label>
    <input type="email" class="form-control">
  </div>
</form>
```

---

## ✏️ Textová pole

Nejčastěji používaná pole:
- `text`
- `email`
- `password`

Každé pole by mělo mít:
- popisek (`label`),
- třídu `form-control`.

---

## 🔽 Výběr z možností

Pro výběr z více možností slouží `select`:

```html
<select class="form-select">
  <option>Možnost 1</option>
  <option>Možnost 2</option>
</select>
```

---

## ☑️ Checkbox a radio

Checkbox:

```html
<input class="form-check-input" type="checkbox">
```

Radio:

```html
<input class="form-check-input" type="radio">
```

---

## 📝 Cvičení

Cvičení k této lekci najdete ve složce **`cviceni/`**.

Každé cvičení má:
- vlastní podsložku (`6.1`, `6.2`, …),
- řešení ve formě HTML souboru.

Postupujte postupně od cvičení **6.1**.
