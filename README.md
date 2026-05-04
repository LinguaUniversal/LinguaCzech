# Lingua · Český jazyk pro 1. stupeň ZŠ — Refresh

**Vizuální refresh** — sjednoceno se stylem **LinguaCzech II** (2. stupeň) a **LinguaDeutsch** (němčina).

## Co se mění

- ✅ **index.html** — nová landing s velkou sovou (jako 2. stupeň + Deutsch)
- ✅ **1trida.html, 2trida.html, 3trida.html** — sjednocený topbar, hero, footer + krásný trofejní board

## Co zůstává

- ✅ **Barvy**: modrá `#32a0d2` + oranžová `#ffaa37`
- ✅ **Font**: Barlow Condensed
- ✅ **Trofeje**: 1.tř. 🥉 100 / 🥈 300 / 🥇 600 · 2.tř. 100/400/800 · 3.tř. 200/600/1200
- ✅ **localStorage klíče** **TOTOŽNÉ** s originálem — žáci nepřijdou o body!
  - 1. třída: `pismena_score`, `cteni_score`
  - 2. třída: `hlasky_score`, `mt_score`, `vh_score`, `sd_score`, `dv_score`, `vm_score`, `vs_score`, `abeceda_slov_score`, `tmo_score`, `slabiky_score`, `cteni2_score`
  - 3. třída: `vyjm_score`, `podst3_score`, `slovesa3_score`, `stsl_score`, `parove3_score`, `slovzas3_score`, `sd3_score`, `ctp3_score`, `osnova_score`
- ✅ **Všechna cvičení** (`pismena.html`, `cteni.html`, `slabiky.html`, ... 30+ stránek) **beze změn**
- ✅ **Přihlášení** (`prihlaseni.html`) funguje (jen tlačítko v indexu)
- ✅ **Učitel/dashboard** (`ucitel.html`, `dashboard.html`) beze změn

## Soubory v ZIPu (4 + logo)

```
index.html       ← Nová landing s velkou sovou
1trida.html      ← 2 cvičení (Písmena, Čtení)
2trida.html      ← 11 cvičení
3trida.html      ← 9 cvičení
logo.png         ← (přepíše stávající, je stejný)
```

## Nahrání

V repu `LinguaCzech` na GitHubu:
1. **"Add file" → "Upload files"** → přetáhni 5 souborů ze ZIPu (přepíše původní)
2. Commit: `Vizuální refresh - sjednocení s LinguaCzech II + LinguaDeutsch`
3. Po 1-2 min se objeví nová verze na `https://linguauniversal.github.io/LinguaCzech/`

**Žáci nepřijdou o body** — localStorage klíče jsou totožné s původní verzí.
