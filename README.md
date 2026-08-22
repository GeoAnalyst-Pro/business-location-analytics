# Business Location Analytics

Geo-analytical siting research for small and mid-size business — location
scoring for restaurants, retail, and service formats based on footfall,
catchment, and competitive-density analysis.

## Methodology
- Catchment-area and footfall estimation
- Competitive-density mapping
- Demographic and income-profile matching to target customer segment
- Rent-to-revenue feasibility scoring
---
## Case: EV Taxi Fleet Transition — Sochi Analytical Map
### Кейс: Аналитическая карта перехода таксопарка на электромобили — Сочи

An interactive, brand-styled decision-support map built for the case study
**"Оценка перехода таксопарка на электромобили" (Sochi, Krasnodar Krai, April
2026)** — prepared for a taxi-fleet operator evaluating a partial transition
to electric vehicles. Available in **English** and **Russian**.

### 🗺️ Open the map / Открыть карту

- 🇬🇧 **[Open the English map](https://geoanalyst-pro.github.io/business-location-analytics/sochi_ev_taxi_map_en.html)**
- 🇷🇺 **[Открыть карту на русском языке](https://geoanalyst-pro.github.io/business-location-analytics/sochi_ev_taxi_map_ru.html)**

*(published via GitHub Pages — opens as a live interactive page; source code
for each file is also browsable directly in this repository) / (опубликовано
через GitHub Pages — открывается как готовая интерактивная страница;
исходный код каждого файла также можно посмотреть прямо в репозитории)*

<summary><b>If the links above show a 404 / Если ссылки выше выдают 404</b></summary>

 As a zero-wait fallback, use htmlpreview.github.io instead — replace
   `main` below with your actual default branch if different:
   - EN: `https://htmlpreview.github.io/?https://github.com/GeoAnalyst-Pro/business-location-analytics/blob/main/sochi_ev_taxi_map_en.html`
   - RU: `https://htmlpreview.github.io/?https://github.com/GeoAnalyst-Pro/business-location-analytics/blob/main/sochi_ev_taxi_map_ru.html`
—
1. Откройте репозиторий и проверьте точные имена файлов (кликните на файл —
   имя видно в заголовке страницы).
2. Убедитесь, что GitHub Pages включён: **Settings → Pages → Source:
   Deploy from a branch → main → / (root)**, и что показана зелёная
   плашка "Your site is live at...".
3. Подождите 1–2 минуты после любого изменения файлов — Pages пересобирается
   не мгновенно.
4. Как быстрый запасной вариант — используйте htmlpreview.github.io
   (ссылки выше в этом же блоке).
</details>

### What the map shows / Что показывает карта

- **Ключевые хабы инфраструктуры**: международный аэропорт, ж/д вокзал,
  морской вокзал и горный курорт Красная Поляна.
- **Сеть зарядных станций**: курируемый именованный набор публичных
  DC-быстрых и AC-станций по городу, с индикативным радиусом охвата 5 км у
  каждой быстрой станции.
- **Переключаемые слои** (справа сверху) — хабы, зарядки, радиусы охвата.
- **Аналитическая панель с вкладками** (слева), все данные — из кейса:
  **Conclusions/Выводы**, **Key Metrics/Ключевые цифры**,
  **TCO (EV vs ICE/ДВС)**, **Fleet & Market/Парк и рынок**.

### Conclusions / Выводы

1. Converting 60% of the fleet (120 of 200 vehicles) to Evolute i-JET EVs
   under a dedicated "ECO COMFORT+" tariff is projected to deliver **8–12%
   total fleet savings over 10 years**. / Перевод 60% парка на Evolute i-JET
   в рамках тарифа «ECO COMFORT+» даёт экономию 8–12% за 10 лет.
2. **Break-even at year 6–7** per vehicle. / Точка безубыточности — 6–7 год
   эксплуатации на 1 авто.
3. **Mountain terrain is the main operational risk** (Krasnaya Polyana
   route) — range drops to 180–220 km on climbs. / Горный рельеф (Красная
   Поляна) — главный операционный риск: запас хода падает до 180–220 км.
4. Sourcing a **Russian-assembled brand (Evolute, Lipetsk)** removes parts-
   logistics risk and qualifies for preferential leasing and a tax
   exemption. / Российский бренд снимает риски логистики и даёт льготный
   лизинг и налоговые льготы.
5. Krasnodar Krai's charging infrastructure is growing **faster than the
   Russian average** (+110% YoY). / Зарядная инфраструктура края растёт
   быстрее среднероссийской.
6. **Recommended fleet mix: 120 EV + 50 hybrid + 30 ICE.** / Рекомендуемая
   структура парка: 120 EV + 50 гибридов + 30 ДВС.

### Data sources / Источники данных

Financial model, market figures, and conclusions: internal case study
*«Оценка перехода таксопарка на электромобили»* (DOMA / GeoAnalyst, 20 April
2026); sources cited therein include Минпромторг, IEA, Statista, Virta
Global, Transport & Environment, АЕБ, Автостат, Argus Media, RBC-Kuban,
ExpertSouth, and the Evolute i-JET dealer manual. Charging-station listings
are a curated public subset (2GIS, EVA Charge network, sochi.spravker.ru);
see inline comments in each HTML file's source for full citation notes and
guidance on sourcing live data for a production version.

### Repository contents / Содержимое репозитория

```
sochi_ev_taxi_map_en.html    # готовая карта на английском
sochi_ev_taxi_map_ru.html    # готовая карта на русском
README.md
```

### Author / Автор

**Zhanna Marchenko / Жанна Марченко** — Chief Project Engineer (NOPRIZ Lvl.
7) / Цифровая аналитика / ГИП, НОПРИЗ 7 уровень · Founder, DOMA LLC (ESG Doma) 

© 2022 ИП Марченко | GeoAnalyst.pro
Все материалы охраняются законодательством РФ об интеллектуальной собственности (ст. 1225–1302 ГК РФ).
Аналитические прогнозы не являются инвестиционной рекомендацией (39-ФЗ).
