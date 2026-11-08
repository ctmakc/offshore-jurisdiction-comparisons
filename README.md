# Offshore jurisdiction comparisons: 10 head-to-head tables

Founders rarely choose a jurisdiction from a list of thirty. They end up weighing two: BVI or Belize for a holding, Delaware or Wyoming for an LLC, Hong Kong or Singapore for Asian trade. This dataset collects ten such pairs and compares them on the parameters a bank, an investor and a tax adviser will ask about: the governing law, the registry, the agent, beneficial ownership filings, annual reporting, tax and the EU list of October 9, 2026. Each table ends with short choice scenarios and links to the full comparison on Offshora.

**Website:** https://ctmakc.github.io/offshore-jurisdiction-comparisons/ · [Русский](https://ctmakc.github.io/offshore-jurisdiction-comparisons/ru/) · [Українська](https://ctmakc.github.io/offshore-jurisdiction-comparisons/uk/)

## Contents

| # | Block | Format | Source (EN / RU / UK) |
|---|---|---|---|
| 01 | BVI vs Belize: Offshore Companies for Holdings and Assets | table | [EN](https://offshora.com/en/comparisons/bvi-vs-belize/) · [RU](https://offshora.com/ru/comparisons/bvi-vs-belize/) · [UK](https://offshora.com/uk/comparisons/bvi-vs-belize/) |
| 02 | BVI vs Seychelles: Which Offshore Jurisdiction to Choose for a Holding Company in 2026 | table | [EN](https://offshora.com/en/comparisons/bvi-vs-seychelles/) · [RU](https://offshora.com/ru/comparisons/bvi-vs-seychelles/) · [UK](https://offshora.com/uk/comparisons/bvi-vs-seychelles/) |
| 03 | Cayman Islands vs BVI for Funds, SPVs and Holding Companies | table | [EN](https://offshora.com/en/comparisons/cayman-vs-bvi/) · [RU](https://offshora.com/ru/comparisons/cayman-vs-bvi/) · [UK](https://offshora.com/uk/comparisons/cayman-vs-bvi/) |
| 04 | Panama vs Nevis: Offshore Company for Trading and Asset Holding | table | [EN](https://offshora.com/en/comparisons/panama-vs-nevis/) · [RU](https://offshora.com/ru/comparisons/panama-vs-nevis/) · [UK](https://offshora.com/uk/comparisons/panama-vs-nevis/) |
| 05 | Delaware vs Wyoming: Which State to Choose for a Non-Resident LLC | table | [EN](https://offshora.com/en/comparisons/delaware-vs-wyoming/) · [RU](https://offshora.com/ru/comparisons/delaware-vs-wyoming/) · [UK](https://offshora.com/uk/comparisons/delaware-vs-wyoming/) |
| 06 | UK Ltd vs US LLC for Non-Residents: Tax, Filings and Banking | table | [EN](https://offshora.com/en/comparisons/uk-ltd-vs-us-llc/) · [RU](https://offshora.com/ru/comparisons/uk-ltd-vs-us-llc/) · [UK](https://offshora.com/uk/comparisons/uk-ltd-vs-us-llc/) |
| 07 | Estonia vs Cyprus: Company Tax and Dividends in 2026 | table | [EN](https://offshora.com/en/comparisons/estonia-vs-cyprus/) · [RU](https://offshora.com/ru/comparisons/estonia-vs-cyprus/) · [UK](https://offshora.com/uk/comparisons/estonia-vs-cyprus/) |
| 08 | Hong Kong vs Singapore: Company Tax, Directors, Reporting | table | [EN](https://offshora.com/en/comparisons/hong-kong-vs-singapore/) · [RU](https://offshora.com/ru/comparisons/hong-kong-vs-singapore/) · [UK](https://offshora.com/uk/comparisons/hong-kong-vs-singapore/) |
| 09 | UAE vs Singapore: Taxes, Free Zones and Company Requirements | table | [EN](https://offshora.com/en/comparisons/uae-vs-singapore/) · [RU](https://offshora.com/ru/comparisons/uae-vs-singapore/) · [UK](https://offshora.com/uk/comparisons/uae-vs-singapore/) |
| 10 | Offshore vs Onshore Company: Which Is More Cost-Effective | table | [EN](https://offshora.com/en/comparisons/offshore-vs-onshore/) · [RU](https://offshora.com/ru/comparisons/offshore-vs-onshore/) · [UK](https://offshora.com/uk/comparisons/offshore-vs-onshore/) |

## Files

- `data/offshore-jurisdiction-comparisons.json` — all blocks with titles, rows or items and source URLs in English, Russian and Ukrainian.
- `data/csv/<lang>/<block>.csv` — one CSV per block and language (`en`, `ru`, `uk`); every row carries its `source_url`.
- `docs/` — the GitHub Pages site (one page per language).

## Example

```python
import json, urllib.request
url = "https://raw.githubusercontent.com/ctmakc/offshore-jurisdiction-comparisons/main/data/offshore-jurisdiction-comparisons.json"
data = json.load(urllib.request.urlopen(url))
for block in data["blocks"]:
    print(block["id"], block["title"]["en"])
```

## Русский

**Сравнение оффшорных юрисдикций: 10 парных таблиц.** Юрисдикцию обычно выбирают из двух вариантов: БВО или Белиз для холдинга, Делавэр или Вайоминг для LLC, Гонконг или Сингапур для торговли с Азией. Здесь собраны десять таких пар. Каждая сравнивается по тем параметрам, о которых спросят банк, инвестор и налоговый консультант: закон, реестр, агент, сведения о бенефициарах, ежегодная отчётность, налоги и список ЕС от 9 октября 2026 года. После таблицы идут короткие сценарии выбора и ссылка на полный разбор на Offshora.

## Українська

**Порівняння офшорних юрисдикцій: 10 парних таблиць.** Юрисдикцію зазвичай обирають із двох варіантів: БВО чи Беліз для холдингу, Делавер чи Вайомінг для LLC, Гонконг чи Сінгапур для торгівлі з Азією. Тут зібрано десять таких пар. Кожну порівняно за параметрами, про які запитають банк, інвестор і податковий консультант: закон, реєстр, агент, відомості про бенефіціарів, щорічна звітність, податки та список ЄС від 9 жовтня 2026 року. Після таблиці йдуть короткі сценарії вибору й посилання на повний розбір на Offshora.

## Sources

Compiled from the free knowledge base of [Offshora](https://offshora.com/), a company formation and corporate services provider: [All jurisdiction comparisons on Offshora](https://offshora.com/en/comparisons/), [Offshore jurisdictions overview](https://offshora.com/en/offshornye-zony.html). Each block links to the page it was taken from; those pages cite the underlying laws and registries.

Rates, fees and deadlines change. Check them with the registry of the jurisdiction before acting. This is reference material and does not replace tax or legal advice.

## Licence

Data: [CC BY 4.0](LICENSE). Corrections are welcome through issues.
