# Lekce 1 – Základy Bootstrapu

V této lekci se seznámíte s frameworkem **Bootstrap**, který slouží k rychlé tvorbě
responzivních webových stránek pomocí hotových tříd a komponent.

Bootstrap nenahrazuje HTML ani CSS – staví na nich a výrazně usnadňuje práci
s rozložením a vzhledem stránky.

---

## 🎯 Cíle lekce

Po absolvování této lekce budete umět:
- vysvětlit, co je Bootstrap a k čemu se používá,
- připojit Bootstrap do HTML stránky pomocí CDN,
- použít základní Bootstrap třídy,
- vytvořit jednoduchý obsah pomocí tříd `container`, `text-center`, `lead`,
- použít základní tlačítka Bootstrapu.

---

## 📦 Připojení Bootstrapu

Bootstrap se nejčastěji připojuje pomocí **CDN**.
Do `<head>` HTML dokumentu vložte:

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
```

Pro správné responzivní chování je nutné také přidat:

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

---

## 🧱 Základní Bootstrap třídy

Mezi nejpoužívanější třídy patří:
- `container` – obsah s omezenou šířkou,
- `text-center` – zarovnání textu na střed,
- `lead` – zvýrazněný úvodní odstavec.

Ukázka:

```html
<div class="container">
  <h1 class="text-center">Moje stránka</h1>
  <p class="lead">Učím se Bootstrap.</p>
</div>
```

---

## 🔘 Tlačítka v Bootstrapu

Tlačítka se vytvářejí pomocí třídy `btn` a barevné varianty.

Nejčastější varianty:
- `btn-primary`
- `btn-success`
- `btn-danger`

Ukázka:

```html
<button class="btn btn-primary">OK</button>
<button class="btn btn-success">Uložit</button>
<button class="btn btn-danger">Smazat</button>
```

---

## 📝 Cvičení

Cvičení k této lekci najdete ve složce **`cviceni/`**.

Každé cvičení má:
- vlastní podsložku (`1.1`, `1.2`, …),
- řešení ve formě HTML souboru.

Postupujte postupně od cvičení **1.1**.

