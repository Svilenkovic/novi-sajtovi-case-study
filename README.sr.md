# Novi sajtovi

Lansiranje i migracija sajta.

**[novisajtovi.com](https://novisajtovi.com/)** · [English](README.md)

> [!NOTE]
> Samostalni projekat D. Svilenkovića. Produkcijski izvor ostaje u privatnom repozitorijumu; ovaj javni repozitorijum dokumentuje izvedeni rad.

<table>
  <tr><td><b>Vrsta</b></td><td>Lansiranje i migracija sajta</td></tr>
  <tr><td><b>Jezici</b></td><td>srpski i engleski</td></tr>
  <tr><td><b>Javne rute</b></td><td>20 canonical stranica</td></tr>
  <tr><td><b>Uloga</b></td><td>istraživanje, dizajn, razvoj, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>Astro, TypeScript, CSS, PHP 8.3, SQLite, nginx</td></tr>
</table>

## Namena

Novi sajt vredi tek kada je prelazak kontrolisan. Projekat objašnjava popis sadržaja, preusmerenja, DNS, provere izdanja i primopredaju redom kojim se stvarno rade.

## Dizajn pravac

Stranica se ponaša kao kontrola lansiranja. Paneli u ponoćno plavoj boji i bakarni indikatori prolaze kroz pripremu, objavu i proveru dok se posetilac kreće niz stranicu.

## Šta je urađeno

- Plan migracije pre bilo kakve DNS promene
- Preusmerenja i očuvanje starih adresa kao deo izrade
- Fazno lansiranje sa proverom na svakoj tački
- Srpski i engleski sadržaj sa odgovarajućim canonical i jezičkim vezama
- Kontakt, privatnost, usluge i proces umesto jedne prodajne stranice

## Provere izdanja

Svaka canonical ruta proverena je na širinama 390, 768, 1440 i 1920 px. Izdanje je provereno i bez JavaScript-a i uz reduced-motion postavku. Žive provere obuhvatile su HTTPS, preusmerenja, zaglavlja odgovora, strukturirane podatke, sitemap fajlove, zaštićene putanje i neispravne kontakt zahteve bez slanja test poruka.

Ovo su inženjerske provere, a ne tvrdnje o poziciji u pretrazi ili terenskim performansama.

---

<sub>Dizajn i izrada: [D. Svilenković](https://svilenkovic.com).</sub>
