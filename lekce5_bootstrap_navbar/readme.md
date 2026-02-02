# Lekce 5 – Navigační menu v Bootstrapu (Navbar)

V této lekci se naučíte vytvořit **navigační menu (navbar)** v Bootstrapu.
Navbar se používá pro odkazy na jednotlivé stránky nebo sekce webu.

Bootstrap navbar je **responzivní** – na menších obrazovkách se menu sbalí do tlačítka (tzv. hamburger menu).

---

## 🎯 Cíle lekce

Po absolvování této lekce budete umět:
- vytvořit základní navbar s názvem webu,
- přidat navigační odkazy pomocí tříd `nav-item` a `nav-link`,
- vytvořit responzivní sbalovací menu pomocí `navbar-toggler` a `collapse`,
- změnit vzhled navbaru (světlý / tmavý),
- zarovnat odkazy doprava pomocí `ms-auto`.

---

## 🧱 Základní navbar

Základní struktura navbaru:

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container">
    <a class="navbar-brand" href="#">Web</a>
  </div>
</nav>
```

Vysvětlení:
- `navbar` – základní třída navigace,
- `navbar-expand-lg` – menu se sbalí až na menších obrazovkách,
- `navbar-light bg-light` – světlý vzhled.

---

## 🔗 Odkazy v navbaru

Odkazy se zapisují jako seznam:

```html
<ul class="navbar-nav">
  <li class="nav-item">
    <a class="nav-link active" href="#">Domů</a>
  </li>
</ul>
```

- `nav-item` – položka seznamu
- `nav-link` – odkaz
- `active` – aktuální stránka

---

## 📱 Responzivní sbalovací menu

Aby se menu na mobilu sbalilo, používá se:
- tlačítko `navbar-toggler`,
- část menu s třídou `collapse navbar-collapse`.

Tato funkce vyžaduje připojený Bootstrap JavaScript (bundle).

---

## ↔️ Zarovnání odkazů

Odkazy lze posunout doprava pomocí třídy `ms-auto`:

```html
<ul class="navbar-nav ms-auto">
  ...
</ul>
```

---

## 📝 Cvičení

Cvičení k této lekci najdete ve složce **`cviceni/`**.

Každé cvičení má:
- vlastní podsložku (`5.1`, `5.2`, …),
- řešení ve formě HTML souboru.

Postupujte postupně od cvičení **5.1**.

