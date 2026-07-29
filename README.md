# Happiness Caffe Bar — Trstenik

Sajt kafića Happiness: početna strana i stranica menija sa cenama.

## Sadržaj

```
index.html      početna (hero, o nama, brzi meni, galerija, kontakt)
meni.html       ceo meni sa slikama i cenama
support.js      runtime potreban za renderovanje stranica
img/            fotografije
```

## Pokretanje lokalno

Otvori `index.html` u pregledaču, ili pokreni lokalni server:

```bash
python3 -m http.server 8000
# pa otvori http://localhost:8000
```

## Objavljivanje na GitHub Pages

1. Napravi novi repozitorijum na GitHubu i push-uj ovaj folder:

```bash
git init
git add .
git commit -m "Happiness Caffe Bar sajt"
git branch -M main
git remote add origin https://github.com/<korisnik>/<repo>.git
git push -u origin main
```

2. U repozitorijumu idi na **Settings → Pages**, pod *Source* izaberi `Deploy from a branch`, granu `main` i folder `/ (root)`, pa sačuvaj.
3. Sajt će biti dostupan na `https://<korisnik>.github.io/<repo>/`.

## Podaci kafića

- Adresa: Cara Dušana 19, Trstenik
- Telefon (porudžbine): 061 730 0202
- Radno vreme: radnim danima 07:30–00:00, vikendom 07:30–01:00

## Napomene

- Fotografije su privremene (stock) — zameni fajlove u `img/` pravim slikama kafića, iste nazive zadrži da ne treba menjati kod.
- Cenovnik pića još nije uključen u meni.
