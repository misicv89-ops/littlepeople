# Little People – Privatni vrtić u Nišu

Statički sajt (HTML/CSS/JS), spreman za GitHub Pages ili bilo koji hosting.

## Struktura
- `index.html` – ceo sajt (desktop + mobilna verzija, responsive)
- `mobilni-pregled.html` – pregled mobilne verzije u okviru telefona (nije deo sajta)
- `images/` – logo, hero, O nama i fotografije aktivnosti
- `support.js`, `image-slot.js` – skripte za prikaz
- `robots.txt`, `sitemap.xml` – SEO

## Objavljivanje na GitHub Pages
1. Napravite novi repozitorijum i otpremite sadržaj ovog foldera u koren.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `root`.
3. Sajt je dostupan na `https://<korisnik>.github.io/<repo>/`.

## Pre objavljivanja
- Zameniti `DOMEN-DOPUNITI.rs` pravim domenom (index.html, robots.txt, sitemap.xml).
- Povezati formu za upis sa servisom za slanje (npr. Formspree) – trenutno samo prikazuje poruku uspeha.
- Sadržaj koji se menja nalazi se u objektu `CONTENT` u `index.html`.
- Stavke označene sa [DOPUNITI] / [PROVERITI] popuniti ili ukloniti.
