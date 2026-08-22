# EV Taxi Fleet Transition — Sochi Analytical Map
### Аналитическая карта перехода таксопарка на электромобили — Сочи

An interactive, brand-styled decision-support map built for the case study
**"Оценка перехода таксопарка на электромобили" (Sochi, Krasnodar Krai, April
2026)** — prepared for a taxi-fleet operator evaluating a partial transition
to electric vehicles. Available in **English** and **Russian**.

- 🇬🇧 **[Open the English map](./output/sochi_ev_taxi_map.html)**
- 🇷🇺 **[Открыть карту на русском языке](./output/sochi_ev_taxi_map_ru.html)**

*(download and open in any modern browser — an internet connection is required
only at view time, to load the CartoDB basemap and Leaflet.js library from
their CDNs)*

---

## Task / Задача

**EN —** A 200-vehicle taxi fleet in Sochi needs a data-backed answer to one
question: does converting part of the fleet to electric vehicles reduce cost
without hurting revenue or reliability — and if so, which part, and under
what operating conditions? This map turns the underlying financial and
market analysis into a spatial, explorable tool: it plots the city's real
charging infrastructure against the fleet's actual operating geography
(airport, stations, mountain resort) so a non-technical decision-maker can
see *where* the economics do and do not hold up, not just read a
spreadsheet.

**RU —** Таксопарку из 200 автомобилей в Сочи нужен обоснованный цифрами
ответ на один вопрос: снижает ли перевод части парка на электромобили
затраты без потери выручки и надёжности — и если да, то какую часть парка
переводить и при каких условиях эксплуатации? Карта превращает финансовый и
рыночный анализ кейса в наглядный, исследуемый инструмент: реальная зарядная
инфраструктура города накладывается на фактическую географию работы парка
(аэропорт, вокзалы, горный курорт), чтобы нетехнический человек, принимающий
решение, увидел, *где именно* экономика сходится, а где нет — а не читал
таблицу цифр.

## What the map shows / Что показывает карта

- **CartoDB Positron basemap** — светлая нейтральная подложка, на которой
  фирменные цвета ДОМА (маркеры, панели) остаются хорошо читаемыми.
- **Ключевые хабы инфраструктуры**: международный аэропорт, ж/д вокзал,
  морской вокзал и горный курорт Красная Поляна — четыре точки, которые
  определяют реальную географию работы парка и его самый рискованный
  маршрут (подъём в горы).
- **Сеть зарядных станций**: курируемый именованный набор публичных
  DC-быстрых и AC-станций по городу (источник — открытые справочники, см.
  раздел *Data sources* ниже), у каждой быстрой станции — индикативный
  радиус охвата 5 км, чтобы оценить реализуемость стратегии "дозаряд между
  сменами".
- **Переключаемые слои** (справа сверху) — можно скрывать/показывать хабы,
  зарядки и радиусы охвата отдельно.
- **Аналитическая панель с вкладками** (справа сверху), все данные — из
  кейса:
  - **Выводы / Conclusions** — шесть выводов для принятия решения
  - **Ключевые цифры / Key Metrics** — операционные и финансовые
    показатели (топливо/энергия, ТО, экономика тарифа, окупаемость)
  - **TCO (EV vs ДВС/ICE)** — полное сравнение совокупной стоимости
    владения за 10 лет на 1 автомобиль
  - **Парк и рынок / Fleet & Market** — рекомендуемая структура парка и
    срез рынка Сочи/края/России
- Английская версия — полностью на английском (для международной аудитории
  и инвесторов); русская версия — полностью на русском. Обе включают
  метрическую линейку масштаба.

## Conclusions (summary) / Выводы (кратко)

1. **RU:** Перевод 60% парка (120 из 200 авто) на Evolute i-JET в рамках
   тарифа «ECO COMFORT+» даёт прогнозную экономию 8–12% по парку за 10 лет
   при ночной зарядке по 3,5 ₽/кВт·ч, 5–10 собственных быстрых DC-станциях
   и строгом зонировании маршрутов.
   **EN:** Converting 60% of the fleet (120 of 200 vehicles) to Evolute
   i-JET EVs under a dedicated "ECO COMFORT+" tariff is projected to deliver
   **8–12% total fleet savings over 10 years**, given night charging at RUB
   3.5/kWh, 5–10 own DC fast chargers, and strict route zoning.
2. Точка безубыточности — 6–7 год эксплуатации на 1 авто. / **Break-even
   occurs at year 6–7** per vehicle.
3. Горный рельеф (Красная Поляна) — главный операционный риск: запас хода
   падает до 180–220 км на подъёме. / **Mountain terrain is the main
   operational risk** — range drops to 180–220 km on climbs.
4. Российский бренд (Evolute, Липецк) снимает риски логистики китайских
   запчастей и даёт льготный лизинг + отмену транспортного налога. /
   Sourcing a **Russian-assembled brand** removes Chinese parts-logistics
   risk and qualifies for preferential leasing and a tax exemption.
5. Зарядная инфраструктура Краснодарского края растёт быстрее, чем в среднем
   по России (+110% в год против ~60–70%). / Krasnodar Krai's charging
   infrastructure is growing **faster than the Russian average**.
6. Рекомендуемая структура парка: **120 EV + 50 гибридов + 30 ДВС**. /
   **Recommended fleet mix: 120 EV + 50 hybrid + 30 ICE.**

## Data sources / Источники данных

- Финансовая модель, рыночные показатели и выводы кейса: внутренний кейс
  *«Оценка перехода таксопарка на электромобили»* (DOMA / GeoAnalyst, 20
  апреля 2026 г.); источники, указанные в самом кейсе: Минпромторг, IEA,
  Statista, Virta Global, Transport & Environment, АЕБ, Автостат, Argus
  Media, RBC-Kuban, ExpertSouth, руководство по эксплуатации дилера Evolute
  i-JET.
- Координаты хабов (аэропорт, ж/д вокзал, морвокзал, Красная Поляна) — по
  общеизвестным географическим ориентирам.
- Список зарядных станций — открытые справочные источники (2ГИС, анонсы
  сети EVA Charge/Intermobility, sochi.spravker.ru) на апрель 2026 г. **Это
  представительная курируемая выборка (11 именованных станций), а не полная
  сеть города** (в кейсе указано ~36 точек на 2026 г.) — среда сборки не
  имеет доступа в интернет для автоматического геокодинга/вызова карто-API.
  Для продакшн-версии замените `CHARGING_STATIONS` в `build_map.py` /
  `build_map_ru.py` на живую выгрузку из Yandex Maps / 2GIS Places API или
  экспорт PlugShare / Chargemap.

## Repository contents / Содержимое репозитория

```
build_map.py              # генерирует английскую версию карты (HTML)
build_map_ru.py           # генерирует русскую версию карты (HTML)
assets/logo.png           # логотип DOMA, встраивается в карту как base64
output/
  sochi_ev_taxi_map.html      # готовая карта на английском
  sochi_ev_taxi_map_ru.html   # готовая карта на русском
README.md
```

## Regenerating the map / Пересборка карты

```bash
python3 build_map.py       # English version
python3 build_map_ru.py    # Русская версия
```

No external Python packages are required — both scripts write a single
self-contained HTML file (Leaflet.js and the CartoDB tiles are loaded from
their public CDNs by the browser at view time, not bundled). / Внешние
Python-пакеты не требуются — оба скрипта создают единый самодостаточный
HTML-файл (Leaflet.js и тайлы CartoDB подключаются браузером из CDN в
момент просмотра, а не встраиваются в файл).

## Author / Автор

**Zhanna Marchenko / Жанна Марченко** — Chief Project Engineer (NOPRIZ Lvl.
7) / ГИП, НОПРИЗ 7 уровень · Founder, DOMA LLC (ESG Doma) ·
[LinkedIn](https://www.linkedin.com/in/jeanna-marchenko-405b9622a/)
