# Apartman Banović · Sokobanja

Sajt apartmana Banović (Svetozara Markovića 1/13, Sokobanja). Jedna stranica, bez dodatnih alata. Radi direktno na GitHub Pages.

## Objavljivanje na GitHub Pages

1. Na github.com napravite novi javni repozitorijum, npr. `apartman-banovic`.
2. Kliknite **Add file › Upload files** i prevucite **ceo sadržaj** ovog foldera (`index.html`, `README.md`, `.nojekyll` i folder `media`). Kliknite **Commit changes**.
3. Otvorite **Settings › Pages**. Pod **Source** izaberite **Deploy from a branch**, grana `main`, folder `/ (root)`, pa **Save**.
4. Posle minut-dva sajt je dostupan na `https://VAŠE-KORISNIČKO-IME.github.io/apartman-banovic/`.

## Posle objavljivanja (preporučeno)

Društvene mreže traže punu adresu slike za pregled linka. U `index.html` zamenite:

```
<meta property="og:image" content="media/og.jpg">
```

sa punom adresom, npr.:

```
<meta property="og:image" content="https://VAŠE-KORISNIČKO-IME.github.io/apartman-banovic/media/og.jpg">
```

## Sopstveni domen (npr. apartmanbanovic.rs)

1. Kupite domen kod registra (.rs domene prodaju ovlašćeni registri).
2. U **Settings › Pages › Custom domain** upišite domen i sačuvajte.
3. Kod registra podesite DNS prema uputstvu GitHub-a (A zapisi ka GitHub Pages adresama, ili CNAME ka `VAŠE-KORISNIČKO-IME.github.io`).
4. Uključite **Enforce HTTPS**.

## Sadržaj

- `index.html`: ceo sajt
- `tura.html`: virtuelna šetnja kroz apartman (dodajete je sami, u isti folder pored `index.html`). Na nju vodi dugme „Prošetajte kroz apartman" u uvodnoj sekciji.
- `media/hero-1080.mp4`: video u uvodnoj sekciji (1080p, ponavlja se bez prekida)
- `media/poster.jpg`: prvi kadar videa, prikazuje se dok se video učitava
- `media/foto/`: fotografije apartmana
- `media/og.jpg`: slika za deljenje na društvenim mrežama
- `media/favicon.svg`, `media/icon-180.png`: ikonice sajta
