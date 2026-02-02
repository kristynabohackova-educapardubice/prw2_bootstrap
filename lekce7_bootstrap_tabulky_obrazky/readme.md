# Lekce 7 – Tabulky a obrázky v Bootstrapu

V této lekci se naučíte používat **tabulky a obrázky v Bootstrapu**. Bootstrap nabízí hotové styly, které zlepší čitelnost tabulek a zajistí, že se obrázky budou správně přizpůsobovat velikosti obrazovky.

---

## 🎯 Cíle lekce

Po absolvování této lekce budete umět:
- vytvořit tabulku pomocí třídy `table`,
- použít styly `table-striped`, `table-bordered` a `table-hover`,
- vytvořit responzivní tabulku pomocí `table-responsive`,
- vložit responzivní obrázek pomocí `img-fluid`,
- upravit vzhled obrázku pomocí `rounded`, `rounded-circle`, `img-thumbnail` a `shadow`.

---

## 📋 Tabulka v Bootstrapu

Základní tabulka:

```html
<table class="table">
  ...
</table>
```

Často používané styly:
- `table-striped` – pruhované řádky,
- `table-bordered` – ohraničení buněk,
- `table-hover` – zvýraznění řádku při najetí myší.

---

## 📱 Responzivní tabulka

Pokud se tabulka nevejde na malou obrazovku, použijte obal:

```html
<div class="table-responsive">
  <table class="table"> ... </table>
</div>
```

Tabulka se pak bude dát na mobilu vodorovně posouvat.

---

## 🖼️ Obrázky v Bootstrapu

Responzivní obrázek:

```html
<img src="foto.jpg" class="img-fluid" alt="Popis">
```

Vzhled obrázku:
- `rounded` – zaoblené rohy,
- `rounded-circle` – kruh,
- `img-thumbnail` – rámeček,
- `shadow` (nebo `shadow-sm`, `shadow-lg`) – stín.

---

## 📝 Cvičení

Cvičení k této lekci najdete ve složce **`cviceni/`**.

Každé cvičení má:
- vlastní podsložku (`7.1`, `7.2`, …),
- řešení ve formě HTML souboru.

Postupujte postupně od cvičení **7.1**.

