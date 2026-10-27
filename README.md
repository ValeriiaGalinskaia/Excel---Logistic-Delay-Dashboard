# Excel---Logistic-Delay-Dashboard
Интерактивный одностраничный дашборд с анализом задержек в международных поставках, отражающий ключевую географию и анализ класса перевозок по количеству задержек.
# Основные Выводы:
* Лидер по задержкам: Люксембург оказался лидером по среднему кол-ву дней задержек, сигнализируя о слабых местах на транзитных путях европейских узлов.
* Несоответствие уровня сервиса (First Class): Приоритетная доставка ("First Class") выявила наибольший риск задержек, отразив неэффективность расходования средств на улучшение сервиса. 
* Регионы с наибольшим риском: Наиболее высокие задержки также наблюдались в Южном Судане и Свазиленде.
# Особенности и архитектура дашборда
* Блок метрик KPI: Отслеживание в реальном времени Общего количества заказов, Риск задержек в процентах, Среднюю задержку в днях.
* Tоп-10 задержек: Визуализируется с использованием  древовидной карты с динамическими метками и отфильтрованными неотрицательными параметрами.
* Интерактивный UX: Перекрестная фильтрация, основанная на срезах с индикаторами прокрутки для выбора по нескольким странам, а также фильтрами по годам и классам перевозки.
# Структура файлов:
* `logistics_dashboard.xlsx` — Главный интерактивный дашборд (Эксель).
* `preview.png` — Скриншот


# Excel---Logistic-Delay-Dashboard
An interactive single-page Excel dashboard designed to analyze international shipment delays, track carrier performance, and highlight key geographical and service-level operational risks.
# Key Operational Insights:
* Unprecedented Regional Delays: Luxembourg emerged as the top country in average delay duration, signaling localized bottlenecks within European hub transit paths.
* Service Level Mismatch (First Class): Priority shipping ("First Class") exhibits the highest risk of delivery delays, indicating inefficient cost-to-performance ratio for expedited services.
* Geographical Risk Hotspots: High delays are consistently tracked across regional destinations including South Sudan and Eswatini.
# Features & Architecture
* KPI Metrics Block: Real-time tracking of Total Orders, Late Delivery Risk, and Average Delay Duration.
* Top-10 Delay Analysis: Visualized using a custom-styled Treemap with dynamic line-break labels and filtered non-negative parameters.
* Interactive UX: Cross-filtering powered by Slicers with explicit scroll indicators for multi-country selection.
# File Structure
* `logistics_dashboard.xlsx` — Main interactive dashboard workbook.
* `preview.png` — Screenshot of the dashboard interface.
