# Rychlý start

## 1. Přehled projektu

Terminator_lite je osobní projekt zaměřený na vývoj robota s využitím hardwaru, senzorů, programování a experimentálních poznatků. Cílem je vytvořit přehledný a rozšiřitelný základ pro další implementaci.

## 2. Struktura repozitáře

```text
Terminator_lite/
├── README.md
├── index.html
├── styles.css
├── assets/
├── docs/
├── .devcontainer/
├── informace o sofrwaru
├── postup
└── ...
```

## 3. Lokální spuštění

### Webová landing page

```bash
cd Terminator_lite
python3 -m http.server 8000
```

Poté otevřete v prohlížeči:

```text
http://localhost:8000
```

### GitHub Codespaces

1. Otevřete repozitář v GitHub.
2. Klikněte na `Code` a poté `Codespaces`.
3. Po spuštění prostředí se otevře připravená konfigurace z `.devcontainer`.
4. Můžete pracovat s dokumentací, upravovat styl a rozšiřovat projekt.

## 4. Doporučené pracovní postupy

- pravidelně aktualizujte dokumentaci
- uchovávejte poznámky o experimentech a výsledcích testů
- rozdělujte projekt do logických částí
- zvažte přidání dalších modulů až po ověření funkčnosti základního prototypu

## 5. Další kroky

- podívejte se na `docs/ROADMAP.md`
- přečtěte si `docs/SOFTWARE_OVERVIEW.md`
- projděte hlavní `README.md` jako hlavní rozcestník projektu
