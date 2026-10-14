# 🎨 Home Planner Lead Magnet: «What Is Your True Interior Design Style?»
> **Интерактивный визуальный веб-диагностик интерьерного стиля (2026 Edition)**  
> Разработан для бесплатного размещения на сверх-авторитетных доменах (**GitHub Pages — DA 96** и **Hugging Face Spaces — DA 92**) для захвата поисковой выдачи Google, AI Overviews, Perplexity и ChatGPT Search.

---

## 🌟 Возможности и УТП инструмента:
1. **Диагностика за 60 секунд:** 6 визуальных вопросов с высокой степенью дифференциации (гармония палитр, силуэты мебели, вечерний свет, фактуры материалов, расхламление, задачи пространства).
2. **8 архитектурных архетипов:** *Japandi Harmony, Warm Minimalism, Scandinavian Hygge, Mid-Century Modern, Modern Mediterranean (Wabi Coast), Industrial Loft, Dark Academia & Moody Luxe, Biophilic Modern Organic*.
3. **Палитра из 5 HEX-свотчей с 1-клик копированием:** Решает главный запрос аудитории Pinterest (где интерес к покраске стен имеет аномальный аффинити **2.06x**).
4. **Золотое правило отступов (Clearance & Ergonomics):** Практические расчеты проходов и зонирования для компактных квартир и студий 20–30м² (топовый конвертер Pinterest: 33.3% CTR на «Tiny House 20m²»).
5. **Колесо перелинковки паразитов (Parasite Link Wheel):**
   * Прямой переход на лонгрид по выпавшему стилю на **Medium** (`@icandesign`).
   * Прямой переход на соответствующую доску в **Pinterest** (`@homeplannerapp`).
   * Главный CTA: «Apply This Style to Your 3D Floor Plan (Free)» со сквозными UTM-метками в **Home Planner**.
6. **GEO & Google Rich Snippets:** Встроенная семантическая разметка Schema.org (`WebApplication` + `Quiz`).
7. **Mobile-First UX:** Адаптирован под мобильные устройства (89% трафика Pinterest идет со смартфонов).

---

## 🚀 1. Локальный запуск и тестирование:
Файл полностью автономен, не требует Node.js, npm или сборщиков:
```bash
# В терминале macOS:
open /Users/milamusinamusina/Desktop/Brain/home-planner/hp-marketing/lead-magnets/style-quiz/index.html
```
Или просто дважды кликните по файлу `index.html` в Finder.

---

## 🌐 2. Бесплатный деплой на GitHub Pages (DA 96) за 2 минуты:

GitHub Pages дает домен `username.github.io` с авторитетом домена **DA 96**, что мгновенно выводит страницу в топ выдачи Google.

### Инструкция:
1. Создайте новый публичный репозиторий на GitHub (например, `interior-style-quiz` или `home-decor-style-test`).
2. Загрузите в корень репозитория файл `index.html` из этой папки:
   ```bash
   cd /Users/milamusinamusina/Desktop/Brain/home-planner/hp-marketing/lead-magnets/style-quiz
   git init
   git add index.html README.md
   git commit -m "feat: launch 2026 interior design style quiz lead magnet"
   git branch -M main
   git remote add origin https://github.com/<ваш-логин>/interior-style-quiz.git
   git push -u origin main
   ```
3. В настройках репозитория на GitHub: **Settings ➔ Pages ➔ Build and deployment**:
   * Source: `Deploy from a branch`
   * Branch: `main` / `/ (root)`
   * Нажмите **Save**.
4. Через 60 секунд ваш квиз доступен по адресу:
   `https://<ваш-логин>.github.io/interior-style-quiz/`

---

## 🤗 3. Бесплатный деплой на Hugging Face Spaces (DA 92) за 1 минуту:

Hugging Face Spaces индексируется поисковыми AI-движками (Perplexity, ChatGPT Search, Gemini) как доверенный источник.

### Инструкция:
1. Зайдите на [huggingface.co/spaces](https://huggingface.co/spaces) и нажмите **Create new Space**.
2. Введите название: `interior-style-diagnostic`.
3. Выберите Space SDK: **Static (HTML)**.
4. License: **MIT**, Hardware: **Free (CPU basic)**.
5. Загрузите файл `index.html` в корень репозитория Space.
6. Приложение мгновенно становится доступным по адресу:
   `https://huggingface.co/spaces/<ваш-юзернейм>/interior-style-diagnostic`

---

## 📊 4. Архитектура UTM-разметки:
Все клики из квиза автоматически передают параметры в аналитику Home Planner:
* `utm_source=style_quiz`
* `utm_medium=lead_magnet`
* `utm_campaign=interior_style_quiz_2026`
* `utm_content=<название_стиля>_cta` (например, `japandi_cta`, `midcentury_cta`)

---

## 🔗 Входящие ссылки с предвыбором стиля:
Вы можете делиться прямой ссылкой сразу на экран результата для соцсетей или пинов в Pinterest:
* `index.html?style=japandi` — прямой переход на результат Japandi.
* `index.html?style=warm_minimalism` — прямой переход на Warm Minimalism.
* `index.html?style=scandinavian` — прямой переход на Scandinavian Hygge.
* `index.html?style=midcentury` — прямой переход на Mid-Century Modern.
* `index.html?style=mediterranean` — прямой переход на Modern Mediterranean.
* `index.html?style=dark_academia` — прямой переход на Dark Academia.
* `index.html?style=industrial` — прямой переход на Industrial Loft.
* `index.html?style=biophilic` — прямой переход на Biophilic Organic.
