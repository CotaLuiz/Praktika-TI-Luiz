# Praktika TI - Zhvillimi i Aplikacioneve Web

## Emri dhe përshkrimi i projektit

Ky projekt është pjesë e detyrës praktike në lëndën e Teknologjisë së Informacionit. Projekti përfshin analizimin dhe përshkrimin e disa modeleve të aplikacioneve web, duke u bazuar në përdorimin e wireframe-ve, funksionaliteteve kryesore dhe teknologjive të përshtatshme për zhvillim.

Modelet e trajtuara në këtë projekt janë:

1. Platformë rekrutimi për zhvillues software-sh.
2. Aplikacion web për menaxhimin e porosive në një piceri.
3. Platformë edukative për universitetin.

Qëllimi i projektit është të paraqesë mënyrën se si mund të ndërtohet një aplikacion web funksional, duke përfshirë regjistrimin e përdoruesve, login, menaxhimin e të dhënave, CRUD, role përdoruesish dhe lidhjen me databazë.

---

## Teknologjitë e përdorura

Teknologjitë e sugjeruara dhe të përdorura për realizimin e projektit janë:

* HTML
* CSS
* JavaScript
* PHP ose Python
* Flask ose Django
* MySQL
* Bootstrap
* GitHub për ruajtjen dhe dokumentimin e projektit

---

## Udhëzimet për instalim dhe ekzekutim lokal

Për ta ekzekutuar projektin në mënyrë lokale, ndiqen këto hapa:

1. Shkarko projektin nga GitHub:

```bash
git clone https://github.com/emri-i-perdoruesit/emri-i-repository.git
```

2. Hyr në folderin e projektit:

```bash
cd emri-i-repository
```

3. Hap projektin në Visual Studio Code ose në një editor tjetër kodi.

4. Nëse projekti është ndërtuar me PHP, vendose folderin brenda `htdocs` në XAMPP dhe hap Apache + MySQL.

5. Krijo databazën në MySQL/phpMyAdmin sipas emrit të përcaktuar në projekt.

6. Importo file-in `.sql`, nëse është përfshirë në projekt.

7. Hap projektin në browser:

```text
http://localhost/emri-i-projektit
```

Nëse projekti është ndërtuar me Python Flask ose Django, instalohen paketat e nevojshme dhe ekzekutohet serveri lokal sipas komandave të framework-ut përkatës.

---

## Struktura e folderave

Struktura e rekomanduar e projektit është:

```text
Praktika-TI/
│
├── README.md
├── docs/
│   └── Praktika_TI_Anxhela_Plotesuar.docx
│
├── assets/
│   ├── images/
│   ├── css/
│   └── js/
│
├── database/
│   └── database.sql
│
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
│
├── backend/
│   ├── config.php
│   ├── auth.php
│   ├── crud.php
│   └── routes/
│
└── wireframes/
    └── wireframe-images/
```

---

## Përshkrimi i roleve të përdoruesve

Në projekt parashikohen disa role përdoruesish, në varësi të modelit të aplikacionit.

### Administrator

Administratori ka të drejtë të menaxhojë përdoruesit, të kontrollojë të dhënat kryesore të sistemit dhe të kryejë veprime të plota CRUD.

### Zhvillues Software-i

Në modelin e platformës së rekrutimit, zhvilluesi mund të krijojë profilin e tij, të shtojë aftësitë teknike dhe të shfaqet si kandidat për organizatat.

### Organizatë

Organizata mund të regjistrohet, të shtojë pozicione pune, të shikojë zhvilluesit e disponueshëm dhe të kontrollojë përputhshmërinë e tyre me pozicionet e hapura.

### Klient

Në modelin e picerisë, klienti mund të regjistrohet, të logohet, të krijojë porosi, të personalizojë picën, të shikojë porositë e mëparshme dhe të finalizojë blerjen.

### Pedagog

Në platformën edukative, pedagogu mund të shtojë leksione, seminare, detyra dhe njoftime për studentët.

### Student

Studenti mund të logohet në sistem, të shikojë materialet mësimore, njoftimet, detyrat dhe informacionet e publikuara nga pedagogët.

---

## Pamje ose shpjegim i faqeve kryesore

### Faqja kryesore

Faqja kryesore prezanton aplikacionin dhe i orienton përdoruesit drejt login-it ose regjistrimit.

### Faqja e regjistrimit

Në këtë faqe përdoruesit krijojnë llogarinë e tyre duke plotësuar të dhënat personale dhe rolin përkatës.

### Faqja e login-it

Faqja e login-it shërben për hyrjen e përdoruesve të regjistruar në sistem. Ajo përfshin validimin e email-it dhe fjalëkalimit.

### Dashboard

Dashboard-i ndryshon sipas rolit të përdoruesit. Administratori sheh menaxhimin e sistemit, organizata sheh kandidatët dhe pozicionet, ndërsa studentët ose klientët shohin informacionet që lidhen me funksionet e tyre.

### Faqet CRUD

Faqet CRUD përdoren për krijimin, leximin, përditësimin dhe fshirjen e të dhënave në sistem. Këto faqe janë të rëndësishme për menaxhimin e përdoruesve, porosive, pozicioneve, materialeve ose detyrave.

### Faqja e profilit

Faqja e profilit i lejon përdoruesit të shikojë dhe të përditësojë të dhënat e tij personale.

---

## Autori dhe viti akademik

**Autori:** Luiz Çota
**Programi i studimit:** Teknologji Informacioni, Viti III
**Universiteti:** Universiteti “Fan S. Noli”, Korçë
**Fakulteti:** Fakulteti i Shkencave Natyrore dhe Shkencave Humane
**Departamenti:** Informatikë
**Viti akademik:** 2024-2025
