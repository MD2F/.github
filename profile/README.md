# MD2F - Markdown 2 File

## Obsah

* [O projektu](#o-projektu)
* [Funkce](#funkce)
* [Instalace](#instalace)
* [Použití](#použití)
* [Příklad](#příklad)
* [Příspěvky](#příspěvky)
* [Licence](#licence)

---

## O projektu

**MD2F** je nástroj pro konverzi Markdown souborů na HTML a další výstupy, s podporou:

* Kompletního GitHub Markdown
* Tabulek, odkazů, obrázků
* Vnořených seznamů, citací a kódu
* Multi-page Markdown souborů
* Automatického fallbacku při chybě načtení souboru

Cílem projektu je poskytovat **jednoduchý, flexibilní a přehledný** nástroj pro práci s Markdown dokumentací.

---

## Funkce

* ✅ Konverze Markdown → HTML
* ✅ Podpora relativních a absolutních URL
* ✅ Fallback soubor při selhání načtení
* ✅ Interaktivní menu pro rychlou navigaci po sekcích
* ✅ Podpora vnořených seznamů (`1.1`, `a.a`) a kombinace `*` / `-`
* ✅ Vnořené citace (`>`) a kódové bloky (`lang`)
* ✅ Stylované výstupy s CSS
* ✅ Multi-page Markdown a taby v HTML
* ✅ Zaměřeno na rychlé webové zobrazení Markdown obsahu

---

## Příklad

```markdown
# Nadpis 1

## Nadpis 2

* Seznam položek
  * Podpoložka
- Další položka

1. Číslovaný seznam
   1.1 Podpoložka
   1.2 Podpoložka

> Citace

**Tucný text**, *kurzíva*

[Odkaz](https://github.com)
![Obrázek](https://via.placeholder.com/150)
```

---

## Licence

Tento projekt je licencován pod **Apache License**.
Viz [LICENSE](LICENSE) pro více informací.

---

© 2025 Jan Poláček
