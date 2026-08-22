## Case: Restaurant Site Selection — Moscow Analytical Map
### Кейс: Геоаналитическое исследование локации под ресторан — Москва

An interactive, brand-styled decision-support map built for the case study
**"Геоаналитическое исследование локации под ресторан"** (Moscow,
Cheryomushkinsky proezd 3k1, near Akademicheskaya metro — DOMA / GeoAnalyst,
2026). Adapted for both desktop and mobile reading. Available in **English**
and **Russian**.

### 🗺️ Open the map / Открыть карту

- 🇬🇧 **[Open the English map](https://geoanalyst-pro.github.io/business-location-analytics/restaurant_location_moscow_en.html)**
- 🇷🇺 **[Открыть карту на русском языке](https://geoanalyst-pro.github.io/business-location-analytics/restaurant_location_moscow_ru.html)**

*(published via GitHub Pages — opens as a live interactive page; works on
both desktop and mobile browsers) / (опубликовано через GitHub Pages —
открывается как готовая интерактивная страница; работает и на компьютере,
и на телефоне)*

> ⚠️ These links only work if the two files in this repository are named
> **exactly** `restaurant_location_moscow_en.html` and
> `restaurant_location_moscow_ru.html`. / Ссылки сработают, только если два
> файла в репозитории названы **точно** так:
> `restaurant_location_moscow_en.html` и `restaurant_location_moscow_ru.html`.

### Task / Задача

**EN —** A small-business operator is evaluating whether to open a
restaurant at a specific Moscow address, Cheryomushkinsky proezd 3k1 (near
Akademicheskaya metro), against two nearby alternative sites. The question:
is there real unmet demand at this address, does the local audience have the
income to support a premium/hybrid format, and what revenue can realistically
be expected in month 1? This map turns the underlying market, audience,
traffic, and financial analysis into a spatial, explorable tool.

**RU —** Владелец малого бизнеса оценивает, стоит ли открывать ресторан по
конкретному адресу в Москве — Черёмушкинский проезд, д. 3, к. 1 (рядом с м.
Академическая), — в сравнении с двумя альтернативными точками поблизости.
Вопрос: есть ли реальный неудовлетворённый спрос по этому адресу, позволяет
ли доход местной аудитории поддержать премиальный/гибридный формат, и какую
выручку реалистично ожидать в первый месяц? Карта превращает анализ рынка,
аудитории, трафика и финансов в наглядный, исследуемый инструмент.

### What the map shows / Что показывает карта

- **CartoDB Positron basemap** — светлая нейтральная подложка.
- **Три рассматриваемые локации**: рекомендованная (Черёмушкинский проезд,
  3к1) и две альтернативы, каждая с попапом с обоснованием.
- **Станция метро «Академическая»** — главный транспортный якорь района.
- **Точки интереса (POI)**: бизнес-центры (два — реальные, проверенные по
  открытым справочникам), школа/клиника/фитнес-клуб (представительные точки
  — иллюстрируют состав POI-микса из кейса, не привязаны к конкретным
  верифицированным адресам, см. раздел *Data sources*).
- **Индикативная зона охвата 1 км** вокруг рекомендованной локации
  (пунктирный круг).
- **Переключаемые слои** (справа сверху): локации, метро/транспорт, POI,
  зона охвата.
- **Аналитическая панель с 4 вкладками** (слева на десктопе, сворачивается
  в кнопку-шторку снизу на телефоне): **Conclusions/Выводы**,
  **Market & Audience/Рынок и аудитория**, **Traffic & Site/Трафик и
  локация**, **Forecast/Прогноз** — все данные из кейса.
- **Источники данных** — тонкая строка внизу карты.
- Полностью на английском ИЛИ полностью на русском (два отдельных файла),
  метрическая линейка масштаба, адаптация под мобильный экран (шапка
  компактнее, панель сворачивается, легенда и переключатель слоёв
  уменьшаются).

### Conclusions (summary) / Выводы (кратко)

1. **RU:** Рекомендованная локация (Черёмушкинский проезд, 3к1) подтверждена
   как готовая к запуску — прибыль прогнозируется с первого месяца работы.
   **EN:** The recommended site is confirmed launch-ready — profitability is
   projected from month 1.
2. Структурный дефицит рынка: расходы аудитории на общепит (122,3 млн ₽)
   более чем вдвое превышают текущую выручку рынка (59,9 млн ₽) — свыше 45%
   спроса не покрыто. / Structural market gap: audience F&B spending
   capacity (RUB 122.3M) more than doubles current market revenue (RUB
   59.9M) — over 45% of demand unmet.
3. 58% из 163 516 человек локальной аудитории — сегмент средний+/премиум,
   что даёт гибридную модель бизнес-ланч + семейный ужин. / 58% of the
   163,516-person audience is средний+/premium income, supporting a hybrid
   lunch+dinner model.
4. 34 652 квартиры плюс бизнес-центры/школы/клиники формируют спрос и днём
   в будни, и вечером в выходные. / 34,652 residential units plus a
   business/school/clinic POI mix create weekday-daytime AND weekend-evening
   demand.
5. Прогноз выручки за 1-й месяц — 3,13 млн ₽ при конверсии всего 2,5% от
   пешеходного трафика. / Projected month-1 revenue: RUB 3.13M at just 2.5%
   conversion from foot traffic.
6. Обе альтернативные локации проигрывают минимум по одному критическому
   параметру — это подтверждает выбор Черёмушкинского проезда. / Both
   alternative sites underperform on at least one critical dimension,
   reinforcing the recommended choice.

### Data sources / Источники данных

Market, audience, traffic, and financial figures: internal case study
*«Геоаналитическое исследование локации под ресторан»* (DOMA / GeoAnalyst,
2026). Site and metro coordinates are approximate placements within the
correct district (Cheryomushki / Akademichesky, South-West Moscow), based on
the street layout shown in the source deck — this build environment has no
live geocoding access, so exact rooftop coordinates were not individually
verified. Two business-center POIs (Микроэкономика at B. Cheryomushkinskaya
34; a business center at Kryzhizhanovskogo 13k3) are real, named locations
found via public search. The school/clinic/fitness-club POIs are
representative placeholders illustrating the POI mix described in the case,
not individually verified addresses — replace `POIS` in
`build_restaurant_map.py` with a live Yandex Maps / 2GIS Places API pull for
a production version.

### Repository contents / Содержимое репозитория

```
build_restaurant_map.py                 # генерирует обе версии карты (EN+RU) из одного файла
assets/logo.png                         # логотип DOMA
output/
  restaurant_location_moscow_en.html    # готовая карта на английском
  restaurant_location_moscow_ru.html    # готовая карта на русском
```

### Regenerating the map / Пересборка карты

```bash
python3 build_restaurant_map.py
```

Both language versions are generated from one shared data structure in a
single script, so the EN and RU maps cannot drift out of sync with each
other. / Обе языковые версии генерируются из одной структуры данных в одном
скрипте — рассинхронизация между EN и RU версиями невозможна.

### Author / Автор

**Zhanna Marchenko / Жанна Марченко** — Chief Project Engineer (NOPRIZ Lvl.
7) / ГИП, НОПРИЗ 7 уровень · Founder, DOMA LLC (ESG Doma) ·
[LinkedIn](https://www.linkedin.com/in/jeanna-marchenko-405b9622a/)
