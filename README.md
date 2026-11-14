# Má ég aðeins 2026 — Lifandi mælaborð

Mælaborð og lokahóf golfhópsins **Má ég aðeins** fyrir tímabilið 2026. Read-only útgáfa ætluð til að hýsa á GitHub Pages og deila með kylfingunum.

18 kylfingar · 9 pör · 20 mót (M9 féll niður) · Hvaleyrarvöllur + útimót (Leynir, Hólmsvöllur, Flúðir, Selfoss)

## Skrár

| Skrá | Hvað |
|---|---|
| `index.html` | Aðalmælaborðið: staðan, MEA meistarinn, Parakeppni, Bikarinn, Ryder Cup, fuglar, næst holu og mótaröðin |
| `player.html` | „Mín síða“: persónuleg síða hvers kylfings |
| `naest-holu.html` | Næst holu · Topp 10 (staðfest af GameBook skjáskotum) |
| `holes.html` | Holuröðun á Hvaleyrarvelli (meðalpunktar á hverri holu) |
| `Lokahof2026.html` | Glærusýning fyrir lokahófið (20 glærur) |
| `KylfingarMyndir/` | Myndir af kylfingunum (notaðar í lokahófinu) |
| `MaEgAdeins2026.png` | Merki hópsins |
| `README.md` | Þessi skrá |

## Keppnirnar

- **MEA meistarinn** — Stableford punktar með forgjöf, **bestu 8 hringir** telja.
- **Parakeppnin** — samanlagðir punktar parsins í parahringjum, **bestu 4 parahringir** telja.
- **Bikarinn** — holukeppni með forgjöf (umferð 1 → 16 manna → 8 manna → undanúrslit → úrslit).
- **Ryder Cup** — Bláir vs Hvítir, Flúðir (Better Ball) og Selfoss (Singles), 18.–19. júlí.
- **Hliðarkeppnir** — fuglar, næst holu (cm og fjöldi), fæst högg (bestu 8 hringir), sigurvegari dagsins.

## Hlekkur fyrir hvern kylfing

`player.html` er með fellilista til að velja kylfing, en líka deep-link í URL:

```
https://goskarsson.github.io/<repo-nafn>/player.html?player=11
```

Player IDs (par í sviga):

- 1 Hlynur (1) · 2 Eva Harpa (1)
- 3 Óli (2) · 4 Kristjana (2)
- 5 Robbi (3) · 6 Begga (3)
- 7 Ási (4) · 8 Berglind (4)
- 9 Maggi (5) · 10 Nína (5)
- 11 Gummi (6) · 12 Björk (6)
- 13 Heisi (7) · 14 Sigrún (7)
- 15 Andri (8) · 16 Rósa (8)
- 17 Sigurgeir (9) · 18 Eva Helga (9)

## Hvað sýnir aðalmælaborðið (index.html)?

- **Haus** með merki hópsins og hnöppum á „Lokahóf 2026“ og „Mín síða“
- **Sía** eftir móti (Allir / M1 … M20) og kyni (Allir / Strákar / Stelpur)
- **Topp 3 karlar og topp 3 konur** (MEA, bestu 8 hringir), með myndum. Smelltu á mynd til að opna síðu kylfingsins.
- **Spjöld:** 🥇 Sigurvegari dagsins · 📊 Topp 5 (bestu 8 hringir) · ⛳ Fæst högg · 🐦 Fuglarnir · 📍 Næst holu · 🎯 Næst holu – fjöldi
- **Myndir og gröf:** súlurit (punktar, högg og forgjöf) · þróun tímabils · Parakeppni · leikforgjöf yfir tíma
- **MEA meistarinn – stigatafla** (hringir sem telja eru merktir, smelltu á dálk til að raða)
- **Parakeppni** – samanlagðir punktar, bestu 4 parahringir
- **Bikarinn 2026** – bracket
- **Ryder Cup 2026** – staða, úrslit hvors dags, lið og allar viðureignir
- **Mótaröðin 2026** – dagskrá

## Hvað sýnir player.html (Mín síða)?

- Val á kylfingi (eða `?player=ID`)
- Hringur fyrir hring – punktar, högg, leikforgjöf og fuglar
- Leikforgjöf yfir tíma (línurit)
- Bikarferill kylfingsins
- Verðlaunaskápur – sjálfvirk merki (t.d. fyrsti hringurinn, 40+ pt, fuglar, næst holu, Bikarinn)

## Úrslitakvöldið er búið

Síðustu þrír hringirnir (M18, M19 og M20) eru nú opnir öllum á bæði `index.html` og `player.html`. Földu gráu punktarnir hafa verið fjarlægðir og hnappurinn **🏆 Lokahóf 2026** efst á mælaborðinu opnar lokahófið.

## Lokahófið (Lokahof2026.html)

Glærusýning í litum hópsins. Fletta með **→ / ←**, bilslá, eða strjúka á síma. **☰** hægra megin opnar yfirlit yfir allar glærur.

1. Lokahóf 2026 – allir kylfingarnir
2. Duglegasti kylfingurinn
3. Parakeppnin (→ birtir 3. sæti, svo toppinn)
4. Besti hringur tímabilsins
5. Holumeistari (→ birtir holurnar í 3 hópum, næsta → setur áherslu á 3 bestu)
6. Ryder Cup
7. Fuglameistari (topp 3 + allir með fleiri en 3 fugla)
8. Bikarinn (Umferð 1 → úrslit)
9. Næst holu · Topp 10 (→ birtir sigurvegarann)
10. Stigataflan (4.–18. sæti)
11. Karla- og kvennaflokkur (→ 3. sæti, → 2. sæti, → sigurvegararnir)
12. 3. sæti
13. 2. sæti
14. MEA meistarinn (niðurtalning + konfettí)
15. Áhugaverðar staðreyndir (→ birtir eina í einu)
16. Bardagi á toppnum (topp 8 · Allir / Strákar / Stelpur)
17. Verðlaunahafar 2026
18.–20. Ráð Gervi Gunnu 1–3 (→ birtir einn kylfing í einu, 6 á hverri glæru)

Lokahófið er hljóðlaust. Myndirnar eru sóttar úr `KylfingarMyndir/` – sú mappa verður að fylgja með upp á GitHub.

## Uppsetning á GitHub Pages (eitt sinn, ~10 mín)

1. Farðu á https://github.com/new, gefðu repo nafn (t.d. `MaEgAdeins2026`), veldu **Public** og „Create repository“.
2. „Add file“ → „Upload files“ → dragðu **allt innihald þessarar möppu** inn (líka `KylfingarMyndir/`) → „Commit changes“.
3. Settings → Pages → Source: „Deploy from a branch“, branch `main`, folder `/ (root)` → Save.
4. Eftir 1–2 mín birtist hlekkurinn, t.d. `https://goskarsson.github.io/MaEgAdeins2026/`

## Uppfærsla eftir mót

1. Taktu skjáskot af leaderboard/skorkortum í Golf GameBook og settu í möppu fyrir mótið (`D…-M…`).
2. Biddu mig um að lesa skorin inn – ég bæti mótinu í `index.html` og `player.html`.
3. Hladdu upp breyttu skránum á GitHub (eða Commit + Push í GitHub Desktop).
4. ~30–60 sek seinna er síðan uppfærð.

## Tækni-glósur

- **Sjálfstæð HTML-skjöl** – eitt skjal per síðu, gögnin innbökuð.
- **Gögn:** grunngögn eru í `<script type="application/json" id="snapshot">` blokk; mót sem bætt var við síðar eru í „data patch“ blokkum (`r12`, `r13` …) og síðustu þrjú mótin í `R18_DATA`, `R19_DATA`, `R20_DATA`.
  - `pts` = Stableford punktar · `str` = högg · `hcp` = leikforgjöf · `bir` = fuglar · `ctp` = næst holu (hola + cm)
- **Mobile-friendly** – virkar á símum.
- **localStorage** – geymir bara persónulegar stillingar (valið mót, sía).

## Leiðréttingar

- 11.11.2026 – Maggi: fugl á 13. holu í M19 bætt við (var 0). Maggi og Gummi eru því jafnir með 15 fugla.
