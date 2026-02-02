# 🎮 Minimal Moves

> Android logická hra zaměřená na dosažení cílového čísla pomocí minimálního počtu tahů.

Minimal Moves je mobilní aplikace vytvořená v Kotlinu s využitím Jetpack Compose.  
Projekt slouží jako školní práce demonstrující návrh aplikace, architekturu MVVM
a práci s lokální databází.

---

## 📱 Náhled aplikace

<p align="center">
  <img src="screenshots/menu.png" width="200"/>
  <img src="screenshots/gameplay.png" width="200"/>
  <img src="screenshots/win.png" width="200"/>
</p>

*(screenshoty jsou ilustrační – můžeš je kdykoliv doplnit)*

---

## 🎯 Cíl projektu

- Vytvořit jednoduchou, ale zábavnou logickou hru
- Použít moderní Android technologie
- Oddělit logiku aplikace od UI
- Navrhnout přehlednou a rozšiřitelnou architekturu

---

## 🧠 Princip hry

- Hráč dostane **počáteční číslo** a **cílové číslo**
- Má k dispozici omezenou sadu matematických operací
- Cílem je dosáhnout cílového čísla na **co nejméně tahů**
- Po dokončení hry je výsledek uložen do historie

---

## ⭐ Hodnocení hráče

Výsledek hry je ohodnocen pomocí hvězdiček:

| Počet tahů | Hodnocení |
|-----------|-----------|
| ≤ 10      | ⭐⭐⭐ |
| 11–20     | ⭐⭐ |
| 21+       | ⭐ |

---

## ✨ Funkce aplikace

- 🎲 Náhodné generování levelů
- ➕ Dynamické operace podle levelu
- ⭐ Hodnocení pomocí hvězdiček
- 🎉 Animace výhry (konfety)
- 📜 Historie odehraných her
- 🗑️ Mazání historie s potvrzovacím dialogem
- 🌙 Podpora tmavého režimu (system default)

---

## 🏗️ Architektura aplikace

Projekt je navržen podle architektury **MVVM**:

