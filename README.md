# Servis klima Knežević — sajt

High-converting jednostranični sajt za **Servis klima Knežević** u Novom Sadu
(montaža i servis klima uređaja). Statički sajt (HTML/CSS/JS), mobile-first,
spreman za **GitHub Pages**.

---

## Podaci (uneti sa Google profila)

| Podatak | Vrednost |
|---------|----------|
| **Telefon** | 061 1140930 (`tel:+381611140930`) |
| **Adresa** | Svetlane Vranić 18, 21000 Novi Sad |
| **Ocena** | 4,9 ★ (74 Google recenzije) |
| **Radno vreme** | Pon–Pet 08:00–20:00 · Sub 08:00–14:00 · Ned zatvoreno |

### Pre slanja klijentu — zameniti
- **Recenzije:** sekcija `#recenzije` sadrži ilustrativne recenzije — zameni ih pravim Google recenzijama.
- Po želji dodaj **fotografije radova / tima** (npr. u hero karticu umesto ilustracije klime).

> Ako neki podatak nije tačan, u `index.html` koristi Find & Replace
> (`+381611140930` / `061 1140930` za telefon, `Svetlane Vranić 18` za adresu).

---

## Lokalno pokretanje

Otvori `index.html` u browseru, ili:

```bash
python -m http.server 8000
# http://localhost:8000
```

## Deploy na GitHub Pages

1. Napravi novi repo (npr. `klima-knezevic`).
2. Push-uj sadržaj ovog foldera u `main`.
3. **Settings → Pages → Source: `main` / root** → Save.
4. Sajt je živ na `https://<korisnik>.github.io/klima-knezevic/`.

`.nojekyll` je uključen.

---

## Dizajn
- **Identitet:** sveža „cool air" tema — svetla vazdušasta podloga, plavo-cijan akcenat
  (`#0ea5e9` → `#06b6d4`) koji asocira na hladan, čist vazduh; animirana ilustracija
  klima uređaja u hero sekciji; Plus Jakarta Sans + Inter tipografija.
- **Optimizovano za telefon:** mobile-first raspored, lepljivo „Pozovite nas" dugme na dnu
  ekrana, klik-za-poziv svuda, brzo učitavanje (bez teških slika), poštuje `prefers-reduced-motion`.

## Struktura
```
klimadzije/
├── index.html
├── styles.css
├── script.js
├── assets/favicon.svg
├── .nojekyll
└── README.md
```
