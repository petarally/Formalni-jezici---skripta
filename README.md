# Formalni jezici — Skripta

Ovo je skripta za kolegij "Formalni jezici". Sadrži poglavlja u zasebnim .tex datotekama (1.tex — 8.tex) i glavni sastavljač main.tex.

## Sadržaj
- Teorija i primjeri za formalne jezike
- Struktura: datoteke 1.tex do 8.tex uključene u main.tex

## Zahtjevi
- TeX distribucija (TeX Live, MiKTeX ili slična)
- Preporučeno: `latexmk` za automatsku kompilaciju

## Kako izgraditi PDF
U direktoriju projekta pokrenite jedan od sljedećih naredbi:

```bash
pdflatex main.tex
# ili, za automatsku višestruku kompilaciju i čišćenje:
latexmk -pdf main.tex
```

Nakon uspješne kompilacije dobit ćete `main.pdf` spreman za pregled.

## Doprinos
PR-ovi su dobrodošli. Ako želite napraviti promjene u skripti, prvo otvorite issue ili pošaljite pull request.

## Licenca
Licenca nije specificirana. Ako želite, dodajte LICENSE datoteku u repozitorij.

---
Autor: petarally
