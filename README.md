# Portfolio

Lični portfolio sajt za prijavu za praksu.

## Sadržaj

- Početna sekcija (hero)
- O meni
- Veštine
- Projekti
- Kontakt

## Pokretanje lokalno

Pošto je ovo statički sajt, dovoljno je da otvoriš `index.html` u browser-u.

## Prilagođavanje

- U `index.html` promeni ime, opis i kontakt podatke.
- U sekciji **Projekti** dodaj svoje stvarne linkove za `Demo` i `GitHub`.
- Po potrebi izmeni boje i stil u `styles.css`.

## Git komande (push na GitHub)

Ako si u folderu repozitorijuma (`Portfolio/Portfolio`), pokreni:

```bash
git add .
git commit -m "Add internship portfolio website"
git push origin main
```

Ako je grana `master`, koristi:

```bash
git push origin master
```

## Predlog za objavu (GitHub Pages)

1. Na GitHub-u otvori repozitorijum.
2. Idi na **Settings > Pages**.
3. U "Build and deployment" izaberi:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (ili `master`), folder `/root`
4. Sačuvaj, pa sačekaj nekoliko minuta.
5. Link sajta će biti prikazan u GitHub Pages sekciji.
