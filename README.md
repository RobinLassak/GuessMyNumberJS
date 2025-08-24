# Hra "Hádej Číslo" - Školní Domácí Cvičení

##  Popis Projektu

Tento projekt představuje jednoduchou webovou hru "Hádej Číslo" vytvořenou jako školní domácí cvičení zaměřené na JavaScript. Hra je interaktivní aplikace, kde hráč musí uhodnout náhodně vygenerované číslo v rozmezí 1-20.

##  Jak Hra Funguje

### Základní Mechanika
- Počítač náhodně vygeneruje číslo mezi 1 a 20
- Hráč má 20 pokusů na uhodnutí správného čísla
- Po každém pokusu dostane nápovědu, zda je jeho číslo vyšší nebo nižší
- Hra sleduje aktuální skóre a nejlepší dosažený výsledek

### Herní Stavy
- **Vítězství**: Hráč uhodne správné číslo → pozadí se změní na zelenou
- **Prohra**: Hráč vyčerpá všech 20 pokusů → pozadí se změní na červenou
- **Neplatný vstup**: Hráč zadá neplatné číslo nebo text → zobrazí se varování

##  Technologie a Struktura Projektu

### Použité Technologie
- **HTML5** - Struktura stránky
- **CSS3/SCSS** - Stylování a responzivní design
- **JavaScript (ES6+)** - Herní logika a interaktivita
- **Bootstrap 5.3.3** - CSS framework pro responzivní layout
- **Prettier** - Formátování kódu

### Struktura Souborů
```
Hra_HadejCislo/
├── index.html          # Hlavní HTML soubor
├── script.js           # JavaScript herní logika
├── package.json        # NPM závislosti
├── package-lock.json   # Zámky verzí
├── .prettierrc         # Prettier konfigurace
└── scss/
    ├── custom.scss     # SCSS styly
    ├── custom.css      # Zkompilované CSS
    └── custom.css.map  # Source map
```

##  Klíčové JavaScript Funkce

### Hlavní Funkcionality
1. **Generování náhodného čísla**: `Math.floor(Math.random() * 20) + 1`
2. **Validace vstupu**: Kontrola, zda je zadaná hodnota platné číslo v rozmezí 1-20
3. **Herní logika**: Porovnání hráčova čísla se skrytým číslem
4. **Správa skóre**: Sledování aktuálního skóre a nejlepšího výsledku
5. **Vizuální feedback**: Změna pozadí podle výsledku hry
6. **Reset hry**: Možnost začít novou hru

### Event Listeners
- **Check Button**: Ověření hráčova tipu
- **Again Button**: Restart hry s novým náhodným číslem

##  Design a UI/UX

### Vizuální Prvky
- **Gradient pozadí**: Barevné přechody pro různé herní stavy
- **Responsivní design**: Přizpůsobení různým velikostem obrazovek
- **Bootstrap komponenty**: Tlačítka, formuláře a grid systém
- **Custom styling**: Vlastní SCSS styly pro herní prvky

### Barevné Schéma
- **Základní stav**: Fialovo-modrý gradient
- **Vítězství**: Zelený gradient
- **Prohra**: Červený gradient

##  Instalace a Spuštění

### Předpoklady
- Node.js a npm (pro instalaci Bootstrap)

### Kroky Instalace
1. **Klonování projektu** (pokud je v git repozitáři)
2. **Instalace závislostí**:
   ```bash
   npm install
   ```
3. **Spuštění aplikace**:
   - Otevřete `index.html` v prohlížeči
   - Nebo použijte lokální server

### Vývoj
- Pro úpravu stylů editujte `scss/custom.scss`
- Pro změnu herní logiky editujte `script.js`

##  Vzdělávací Cíle

### JavaScript Koncepty
- **DOM manipulace**: Výběr a úprava HTML elementů
- **Event handling**: Reakce na uživatelské akce
- **Proměnné a scope**: Správa herního stavu
- **Podmíněné výrazy**: Logika hry
- **Funkce**: Organizace kódu
- **Strict mode**: `'use strict'` pro lepší debugging

### Web Development
- **HTML struktura**: Sémantické značení
- **CSS styling**: Responzivní design
- **Bootstrap framework**: Použití CSS frameworku
- **SCSS**: Preprocessor pro CSS

## Možná Vylepšení

### Funkční Rozšíření
- Přidání zvukových efektů
- Různé obtížnosti (větší rozsah čísel)
- Statistiky her
- Multiplayer režim

### Technická Vylepšení
- LocalStorage pro ukládání nejlepšího skóre
- Animace a přechody
- Accessibility features
- Unit testy

##  Poznámky

Tento projekt demonstruje základní koncepty JavaScript programování v kontextu webové hry. Je vhodný pro začátečníky, kteří se učí DOM manipulaci, event handling a základní programovací logiku.

---

**Autor**: Robin Lassak  
**Technologie**: HTML5, CSS3, JavaScript, Bootstrap, SCSS  
**Typ**: Interaktivní webová hra

