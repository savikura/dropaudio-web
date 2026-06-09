# DROPAUDIO Layer 4 — Vizualinis tikrinimas

Tikrinti lokaliai: atidaryti `index.html` naršyklėje per `file://` arba lokalų serverį.  
Kiekvienam puslapiui: **LT → EN → mobile (375px)**.

---

## Bendri patikrinimai (kiekvienas puslapis)

- [ ] Kalba persijungia LT ↔ EN — visi tekstai pasikeičia, nė vienas nelieka angliškas LT versijoje
- [ ] Navigacijos meniu rodomas teisingai (desktop ir mobile hamburger)
- [ ] Footer rodomas teisingai — paslaugų sąrašas, kontaktai
- [ ] Puslapio pavadinimas `<title>` atitinka turinį (patikrinti naršyklės skirtuke)
- [ ] Nėra tuščių teksto blokų (`data-t` elementai be teksto)
- [ ] Nėra matomų `[object Object]` ar `undefined` tekstų
- [ ] Nuorodos navigacijoje veikia (ne 404)
- [ ] CTA mygtukas "Rašyti mums" / "Write to us" — nuoroda į kontaktai.html

---

## Puslapių sąrašas

### Pagrindinis
- [ ] **index.html** — hero tekstas, YouTube video groja, statistikų blokas (19+, 900+), paslaugų kortelės, apie mus sekcija

### Apie
- [ ] **apie.html** — statistikos: 19 metų, 900 balsų; komandos nuotraukos ir aprašymai; istorijos sekcija; klientų logotipai

### Paslaugos (apžvalga)
- [ ] **paslaugos.html** — visų paslaugų sąrašas, nuorodos į kiekvieną veikia

### Paslaugų puslapiai (su related kortelėmis)
- [ ] **angliskas-igarsinimas.html** — rel kortelės rodomos, tekstai LT/EN
- [ ] **animacijos-igarsinimas.html** — rel kortelės rodomos
- [ ] **audio-gidu-igarsinimas.html** — rel kortelės
- [ ] **audio-reklamos.html** — rel kortelės
- [ ] **audiobrandingas.html** — rel kortelės
- [ ] **audioknygos-igarsinimas.html** — rel kortelės
- [ ] **estiskas-igarsinimas.html** — rel kortelės
- [ ] **filmu-igarsinimas.html** — rel kortelės
- [ ] **garso-adaptacija.html** — rel kortelė "Animacijos ir filmukų įgarsinimas" (ne "audioknygų")
- [ ] **garso-dizainas.html** — rel kortelės; "nuosavą garso biblioteką" (ne "proprietary")
- [ ] **igarsinimas-uzsienio-kalba.html** — rel kortelės
- [ ] **ivr.html** — rel kortelės
- [ ] **latviskas-igarsinimas.html** — rel kortelės
- [ ] **mokomuju-klipu-igarsinimas.html** — rel kortelės
- [ ] **muzikos-kuryba.html** — rel kortelė "Animacijos ir filmukų įgarsinimas" (ne "audioknygų")
- [ ] **rusiskas-igarsinimas.html** — rel kortelės
- [ ] **serialu-dublazas.html** — rel kortelės
- [ ] **tv-reklamos.html** — "19 metų patirtis" (ne 17); rel kortelės

### Kiti puslapiai
- [ ] **balsai.html** — balsų sąrašas / filtravimas veikia
- [ ] **visi-darbai.html** — Vimeo vaizdo įrašai groja (28 vnt.)
- [ ] **klientai.html** — logotipai rodomi
- [ ] **kontaktai.html** — adresas, el. paštas, telefonas teisingi
- [ ] **es-parama.html** — turinys rodomas
- [ ] **privatumo-politika.html** — turinys rodomas

---

## Specifiniai patikrinimai

### Statistikos (pataisytos Layer 3)
- [ ] `apie.html` — rodo **19** metų (ne 17), **900** balsų
- [ ] `paslaugos.html` — "19 metų dirbame" LT ir EN
- [ ] `tv-reklamos.html` — "19 metų patirtis" LT ir EN

### Rel kortelių pavadinimai (pataisytos Layer 3)
- [ ] `garso-adaptacija.html` rel_2 → "Animacijos ir filmukų įgarsinimas"
- [ ] `muzikos-kuryba.html` rel_3 → "Animacijos ir filmukų įgarsinimas"

### Layer 2 taisymų vizualinis patikrinimas
- [ ] `garso-dizainas.html` — "nuosavą garso biblioteką" (ne "proprietary")
- [ ] `audio-gidu-igarsinimas.html` — "Atrenkamas balsas" (ne "Atrenkami")
- [ ] `audioknygos-igarsinimas.html` — "Mes atrenkame naratorių" (ne "atrenkami")
- [ ] `muzikos-kuryba.html` — "miksas" (ne "mixas"), "atskiri instrumentai" (ne "separate")

---

## Mobile (375px plotis)

Patikrinti bent šiuos:
- [ ] `index.html` — hero, navigacija, paslaugų kortelės
- [ ] Bet kuris paslaugos puslapis — sidebar, rel kortelės
- [ ] `apie.html` — komandos sekcija
- [ ] `kontaktai.html` — kontaktų blokas

---

## Žymėjimas

Radus klaidą — pažymėti failo pavadinimą ir aprašyti problemą, perduoti taisymui.
