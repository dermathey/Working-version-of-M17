# M17 — показатели анализа кожи

> Карточка на каждый показатель, который упоминают руководство M17 (`devices/m17/m17-user-manual.md`) и брошюра (`devices/m17/m17-brochure-en.md`). Руководство — уровень доверия 2, брошюра — уровень 4 (маркетинг). Описания «что измеряет» есть только в брошюре. Это утверждения производителя, а не проверенные факты.
>
> **Правила:** ничего не додумано; нет в источнике → «нет данных». Ссылка `путь:строка` указывает на строку в сыром источнике (папки `devices/`, `brands/`, `clinic/`, `textbooks/`). Уровни доверия к источникам — `rules/source-hierarchy.md`, известные проблемы — `rules/KNOWN_ISSUES.md`.

## Общее для всех показателей

- **Шкала.** Брошюра: «presented as scores—higher scores indicate better skin condition, lower scores indicate poorer skin condition» (`devices/m17/m17-brochure-en.md:142`). Руководство: «The score-based quantitative analysis results are clear at a glance» (`devices/m17/m17-user-manual.md:794`). **Диапазон баллов, пороги и нормы — нет данных.**
- **Источники света аппарата.** Руководство: «RGB+UV+PL tri-spectrum» (`devices/m17/m17-user-manual.md:154`) и «Spectrums: 10 Spectrums» (`devices/m17/m17-user-manual.md:387`) — **расхождение внутри руководства**. Брошюра: «10-Spectrum Imaging» (`devices/m17/m17-brochure-en.md:42`), «combining RGB light, UV light, cross-polarized, and parallel-polarized light sources» (`devices/m17/m17-brochure-en.md:142`).
- **Число показателей.** Руководство: «The top 10 deep skin issues are analyzed» (`devices/m17/m17-user-manual.md:766`), «12 kinds of analysis» (`devices/m17/m17-user-manual.md:823`), при этом на рисунке 4-2 перечислено 18 показателей (`devices/m17/m17-user-manual.md:771`–790). Брошюра: «Analyze 18 skin issues, 5 problem types & future aging» (`devices/m17/m17-brochure-en.md:44`). **Расхождение.**
- **Условия съёмки, влияющие на точность** (руководство, п. 7.4.1): волосы в кадре — «may be misinterpreted as pigmented spots» (`devices/m17/m17-user-manual.md:730`); макияж — «leading to biased data» (`devices/m17/m17-user-manual.md:733`); положение головы (`devices/m17/m17-user-manual.md:735`); внешний свет — «be sure to use a Hood» (`devices/m17/m17-user-manual.md:739`).
- **Отчёт аппарата** (проверено на разборе от 17.09.2026): текстовые блоки отчёта и сводный экран (Comprehensive / Skin Indicators) **не использовать и клиенту не показывать**; сравнение во времени — только по детальным вкладкам; при расхождении балла с картой или фото — опираться на фото и очную оценку. Подробно — `rules/KNOWN_ISSUES.md`, строка «Отчёт M17».
- **Русские названия** ниже — перевод для удобства, **не из источника**: интерфейс аппарата в источниках только на английском.
- **Категории (брошюра):** Cleansing, Pigmentation, Sensitivity, Acne, Anti-aging (`devices/m17/m17-brochure-en.md:116`). В перечне категорий брошюры есть «Comedo» (`devices/m17/m17-brochure-en.md:120`), а в списке отчётов его нет, зато есть «Pimple» — **расхождение**.

## Показатели (18)

### Pore — Поры (расширенные)

- **Название в аппарате (EN):** Pore (список показателей в руководстве: `devices/m17/m17-user-manual.md:771`) · **RU:** Поры (расширенные) _(перевод, не из источника)_
- **Категория (брошюра):** Cleansing
- **Слой:** Epidermis
- **Что измеряет (брошюра, маркетинг):** «Detects enlarged pores in the epidermis layer.» (`devices/m17/m17-brochure-en.md:240`)
- **Спектр / свет:** нет данных (в карточке не указан)
- **Как читать:** «In the image, red marks indicate areas with severe enlarged pores in the epidermis, while green marks indicate areas with mild enlarged pores.» (`devices/m17/m17-brochure-en.md:244`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Skin rejuvenation, cleansing, and other relevant procedures can effectively improve this issue.» (`devices/m17/m17-brochure-en.md:250`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:236`
- **Ограничения и расхождения:** сверх общих (см. выше) — нет данных

### Porphyrin — Порфирины

- **Название в аппарате (EN):** Porphyrin (список показателей в руководстве: `devices/m17/m17-user-manual.md:772`) · **RU:** Порфирины _(перевод, не из источника)_
- **Категория (брошюра):** Cleansing
- **Слой:** нет данных
- **Что измеряет (брошюра, маркетинг):** «Porphyrins are metabolic products of bacteria on the skin surface (especially Propionibacterium acnes).» (`devices/m17/m17-brochure-en.md:256`)
- **Спектр / свет:** «Under specific wavelengths of light, porphyrins will emit a specific color of fluorescence» (в разделе спектров: UV Wood Light — «Porphyrins» `devices/m17/m17-brochure-en.md:182`)
- **Как читать:** «The pink and white areas on the map are white dots, and porphyrins appear as bright spots or bright areas on the map.» (`devices/m17/m17-brochure-en.md:260`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Cleaning, degreasing and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:264`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:252`
- **Ограничения и расхождения:** Фраза «The pink and white areas on the map are white dots» бессвязна (машинный перевод) (`devices/m17/m17-brochure-en.md:260`)

### Sebum — Себум (кожное сало)

- **Название в аппарате (EN):** Sebum (список показателей в руководстве: `devices/m17/m17-user-manual.md:774`) · **RU:** Себум (кожное сало) _(перевод, не из источника)_
- **Категория (брошюра):** Cleansing
- **Слой:** Surface (поверхность)
- **Что измеряет (брошюра, маркетинг):** «Through PL parallel light illumination, the oil secretion of the skin can be effectively checked, and the interaction between oil and light source can be increased to highlight the degree and distribution of oil problems.» (`devices/m17/m17-brochure-en.md:272`)
- **Спектр / свет:** «Through PL parallel light illumination» (`devices/m17/m17-brochure-en.md:272`)
- **Как читать:** «The image uses yellow marks to mark the problem areas in a gradient color.» (`devices/m17/m17-brochure-en.md:276`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Skin rejuvenation, cleaning, and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:280`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:266`
- **Ограничения и расхождения:** сверх общих (см. выше) — нет данных

### Clogged Pore — Закупоренные поры / чёрные точки

- **Название в аппарате (EN):** Clogged Pore (список показателей в руководстве: `devices/m17/m17-user-manual.md:775`) · **RU:** Закупоренные поры / чёрные точки _(перевод, не из источника)_
- **Категория (брошюра):** Cleansing
- **Слой:** нос («at the tip of the nose»)
- **Что измеряет (брошюра, маркетинг):** «Detect the distribution of blackheads.» (`devices/m17/m17-brochure-en.md:286`)
- **Спектр / свет:** «Combining a specific band light source» — диапазон не указан (`devices/m17/m17-brochure-en.md:286`)
- **Как читать:** «Use black markers to mark the distribution and size of blackheads in the selected area of the nose.» (`devices/m17/m17-brochure-en.md:290`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Skin rejuvenation, cleaning, and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:294`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:282`
- **Ограничения и расхождения:** сверх общих (см. выше) — нет данных

### Epidermis Pigment — Пигмент эпидермиса

- **Название в аппарате (EN):** Epidermis Pigment (список показателей в руководстве: `devices/m17/m17-user-manual.md:776` — в руководстве разбито на две строки) · **RU:** Пигмент эпидермиса _(перевод, не из источника)_
- **Категория (брошюра):** Pigmentation
- **Слой:** Epidermis
- **Что измеряет (брошюра, маркетинг):** «Through the auxiliary illumination of RGB light source, the color spots are displayed more clearly, and the color spots on the surface of the skin are identified and screened by the color difference between the color of the spots and the skin color.» (`devices/m17/m17-brochure-en.md:302`)
- **Спектр / свет:** «Through the auxiliary illumination of RGB light source» (`devices/m17/m17-brochure-en.md:302`)
- **Как читать:** «Detects deeper pigmentation issues in the skin, with red and green markings highlighting the location and shape of deeper spots.» (`devices/m17/m17-brochure-en.md:306`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Products such as freckle removal and picosecond freckle removal have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:310`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:296`
- **Ограничения и расхождения:** В «Viewing Method» описаны **глубокие** пятна — текст, вероятно, скопирован из Dermis Pigment (`devices/m17/m17-brochure-en.md:306`)

### Dermis Pigment — Пигмент дермы

- **Название в аппарате (EN):** Dermis Pigment (список показателей в руководстве: `devices/m17/m17-user-manual.md:778`) · **RU:** Пигмент дермы _(перевод, не из источника)_
- **Категория (брошюра):** Pigmentation
- **Слой:** Dermis (подзаголовок карточки при этом «Skin Surface Pigmentation» — ошибка)
- **Что измеряет (брошюра, маркетинг):** «UV Wood's light has the characteristic of penetrating the surface of the skin and can reach deeper skin tissue to observe the condition of dark spots.» (`devices/m17/m17-brochure-en.md:318`)
- **Спектр / свет:** «UV Wood's light»; в разделе спектров UV Wood 320–400 nm (`devices/m17/m17-brochure-en.md:182`)
- **Как читать:** «Detect deep skin pigmentation.» (`devices/m17/m17-brochure-en.md:322`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Freckle removal, pigmentation and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:326`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:312`
- **Ограничения и расхождения:** Подзаголовок «Skin Surface Pigmentation» противоречит названию (`devices/m17/m17-brochure-en.md:312`)

### Brown Area — Коричневая зона (пигмент базального слоя)

- **Название в аппарате (EN):** Brown Area (список показателей в руководстве: `devices/m17/m17-user-manual.md:779`) · **RU:** Коричневая зона (пигмент базального слоя) _(перевод, не из источника)_
- **Категория (брошюра):** Pigmentation
- **Слой:** Basal Layer
- **Что измеряет (брошюра, маркетинг):** «The brown spot image is formed by extracting and combining specific bands in the auxiliary light source.» (`devices/m17/m17-brochure-en.md:334`)
- **Спектр / свет:** в разделе спектров: «brown light of specific wavelengths (usually 590–620nm)» (`devices/m17/m17-brochure-en.md:206`)
- **Как читать:** «This image primarily examines basal (mid-layer) pigmentation.» (`devices/m17/m17-brochure-en.md:338`). Числовые пороги — нет данных.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:328`
- **Ограничения и расхождения:** В разделе спектров: «pigments related to tyrosinase activity (such as melanin and hemoglobin)» — гемоглобин к тирозиназе не относится (`devices/m17/m17-brochure-en.md:206`)

### UV Damage — УФ-повреждение

- **Название в аппарате (EN):** UV Damage (список показателей в руководстве: `devices/m17/m17-user-manual.md:780`) · **RU:** УФ-повреждение _(перевод, не из источника)_
- **Категория (брошюра):** Pigmentation
- **Слой:** Dermis (раздел спектров)
- **Что измеряет (брошюра, маркетинг):** «After illuminating the skin with specific spectral light, a fluorescence reaction is triggered.» (`devices/m17/m17-brochure-en.md:226`)
- **Спектр / свет:** «exposure to low-frequency, long-wave UVA» (`devices/m17/m17-brochure-en.md:226`)
- **Как читать:** нет данных. Числовые пороги — нет данных.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:220`
- **Ограничения и расхождения:** сверх общих (см. выше) — нет данных

### Melasma — Мелазма

- **Название в аппарате (EN):** Melasma (список показателей в руководстве: `devices/m17/m17-user-manual.md:781`) · **RU:** Мелазма _(перевод, не из источника)_
- **Категория (брошюра):** Pigmentation
- **Слой:** Dermis (раздел спектров)
- **Что измеряет (брошюра, маркетинг):** «Green light with a wavelength of 520–560 nm can penetrate the epidermis and is preferentially absorbed by hemoglobin and melanin, forming a green-toned image based on reflection differences.» (`devices/m17/m17-brochure-en.md:218`)
- **Спектр / свет:** «specific light source (wavelength 520-560nm)»; «pseudo-color display enhanced by the algorithm» (`devices/m17/m17-brochure-en.md:218`)
- **Как читать:** нет данных. Числовые пороги — нет данных.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:212`
- **Ограничения и расхождения:** сверх общих (см. выше) — нет данных

### Sensitive Area — Чувствительные зоны (красная зона)

- **Название в аппарате (EN):** Sensitive Area (список показателей в руководстве: `devices/m17/m17-user-manual.md:782`) · **RU:** Чувствительные зоны (красная зона) _(перевод, не из источника)_
- **Категория (брошюра):** Sensitivity
- **Слой:** Dermis
- **Что измеряет (брошюра, маркетинг):** «Based on the optical response of the spectrum to different substances, the facial capillary lines can be extracted and displayed well.» (`devices/m17/m17-brochure-en.md:398`)
- **Спектр / свет:** карточка: «Through the reflection reaction of UV light and hemoglobin»; раздел спектров: «Red light (wavelength 630–700nm)» (`devices/m17/m17-brochure-en.md:198`)
- **Как читать:** «This question primarily examines skin sensitivity.» (`devices/m17/m17-brochure-en.md:402`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Desensitization, stability maintenance and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:406`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:392`
- **Ограничения и расхождения:** Источник света указан по-разному: UV в карточке, красный 630–700 nm в разделе спектров (`devices/m17/m17-brochure-en.md:398`); «acne will form in the next 2-3 days» — утверждение без подтверждения (KNOWN_ISSUES) (`devices/m17/m17-brochure-en.md:402`)

### Spider Vein — Сосудистые звёздочки / капилляры

- **Название в аппарате (EN):** Spider Vein (список показателей в руководстве: `devices/m17/m17-user-manual.md:783`) · **RU:** Сосудистые звёздочки / капилляры _(перевод, не из источника)_
- **Категория (брошюра):** Sensitivity
- **Слой:** нет данных
- **Что измеряет (брошюра, маркетинг):** «Based on the optical response of the spectrum to different substances, this device primarily uses cross-polarized light or specific red wavelengths (approximately 540-560nm) to capture the state of skin hemoglobin.» (`devices/m17/m17-brochure-en.md:382`)
- **Спектр / свет:** «cross-polarized light or specific red wavelengths (approximately 540-560nm)» (`devices/m17/m17-brochure-en.md:382`)
- **Как читать:** «The more obvious the red area in the picture and the denser the distribution, the more serious the problem.» (`devices/m17/m17-brochure-en.md:386`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Desensitization, stability maintenance and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:390`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:376`
- **Ограничения и расхождения:** 540–560 nm — зелёный, а не красный диапазон; ошибка источника (KNOWN_ISSUES) (`devices/m17/m17-brochure-en.md:382`)

### Thermal — Тепловая карта чувствительности

- **Название в аппарате (EN):** Thermal (список показателей в руководстве: `devices/m17/m17-user-manual.md:784`) · **RU:** Тепловая карта чувствительности _(перевод, не из источника)_
- **Категория (брошюра):** Sensitivity
- **Слой:** Dermis (раздел спектров)
- **Что измеряет (брошюра, маркетинг):** «Polarized PL light filters the reflections from facial oil and light sources, effectively blocking unwanted light interference and allowing for a clearer view of facial sensitivity, inflammation, and redness.» (`devices/m17/m17-brochure-en.md:414`)
- **Спектр / свет:** «Polarized PL light»; в разделе спектров «multiple specific spectral lights and combining algorithmic analysis» (`devices/m17/m17-brochure-en.md:414`)
- **Как читать:** «Highlights facial sensitivity, mainly used to view the distribution and range of different levels of sensitivity across the face, echoing the red zone map.» (`devices/m17/m17-brochure-en.md:418`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Desensitization, stability maintenance and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:422`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:408`
- **Ограничения и расхождения:** Подаётся как карта температуры, хотя строится по оптическим снимкам; тепловизора в характеристиках нет. Утверждение производителя, не факт (KNOWN_ISSUES) (`devices/m17/m17-brochure-en.md:210`)

### Acne — Акне / воспалительные элементы

- **Название в аппарате (EN):** Acne (список показателей в руководстве: `devices/m17/m17-user-manual.md:773`) · **RU:** Акне / воспалительные элементы _(перевод, не из источника)_
- **Категория (брошюра):** Acne
- **Слой:** нет данных
- **Что измеряет (брошюра, маркетинг):** нет данных
- **Спектр / свет:** «Using RGB light»
- **Как читать:** нет данных. Числовые пороги — нет данных.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:130`
- **Ограничения и расхождения:** В связанных процедурах указаны «Anti-aging, skin rejuvenation» — вероятна ошибка копирования (`devices/m17/m17-brochure-en.md:438`)

### Pimple — Прыщи

- **Название в аппарате (EN):** Pimple (список показателей в руководстве: `devices/m17/m17-user-manual.md:785`) · **RU:** Прыщи _(перевод, не из источника)_
- **Категория (брошюра):** нет данных (в перечне категорий брошюры не упомянут)
- **Слой:** нет данных
- **Что измеряет:** нет данных
- **Спектр / свет:** нет данных
- **Как читать:** нет данных
- **Ограничения и расхождения:** Отдельной карточки в брошюре нет; показатель есть только в списках (`devices/m17/m17-brochure-en.md:548`)

### Wrinkle — Морщины

- **Название в аппарате (EN):** Wrinkle (список показателей в руководстве: `devices/m17/m17-user-manual.md:786`) · **RU:** Морщины _(перевод, не из источника)_
- **Категория (брошюра):** Anti-aging
- **Слой:** Epidermis («epidermal wrinkle problems»)
- **Что измеряет (брошюра, маркетинг):** «Identify facial fine lines based on the problematic features of facial stripes, mark the surface skin texture and subtle collagen loss lines.» (`devices/m17/m17-brochure-en.md:446`)
- **Спектр / свет:** нет данных
- **Как читать:** «Detect epidermal wrinkle problems.» (`devices/m17/m17-brochure-en.md:450`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Anti-aging, skin rejuvenation, wrinkle removal and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:454`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:440`
- **Ограничения и расхождения:** Подзаголовок «Distribution of superficial acne» — ошибка копирования; «Sichuan wrinkles» — машинный перевод (межбровные морщины) (`devices/m17/m17-brochure-en.md:442`)

### Texture — Текстура / шероховатость

- **Название в аппарате (EN):** Texture (список показателей в руководстве: `devices/m17/m17-user-manual.md:788`) · **RU:** Текстура / шероховатость _(перевод, не из источника)_
- **Категория (брошюра):** Anti-aging
- **Слой:** Epidermis
- **Что измеряет (брошюра, маркетинг):** «T hrough screening and classification of light and shadow and color characteristics of different problems, it detects facial unevenness caused by large pores, wrinkles, acne, and moles, reflects the smoothness of the face, and has obvious prominence on acne, wrinkles, and moles.» (`devices/m17/m17-brochure-en.md:462`)
- **Спектр / свет:** нет данных («screening and classification of light and shadow and color characteristics»)
- **Как читать:** «Detect the smoothness and flatness of the epidermis.» (`devices/m17/m17-brochure-en.md:466`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Anti-aging, skin rejuvenation, wrinkle removal and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:470`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:456`
- **Ограничения и расхождения:** сверх общих (см. выше) — нет данных

### Moisture — Увлажнённость

- **Название в аппарате (EN):** Moisture (список показателей в руководстве: `devices/m17/m17-user-manual.md:789`) · **RU:** Увлажнённость _(перевод, не из источника)_
- **Категория (брошюра):** Anti-aging
- **Слой:** «Deep Skin Dehydration Detection»
- **Что измеряет (брошюра, маркетинг):** «Based on the UV absorption characteristics of different substances, when UV rays strike a surface, water molecules absorb specific wavelengths of light energy.» (`devices/m17/m17-brochure-en.md:478`)
- **Спектр / свет:** «Based on the UV absorption characteristics» (`devices/m17/m17-brochure-en.md:478`)
- **Как читать:** «Deep Skin Dehydration Detection · **Marking**: Purple = severe, Dark Blue = moderate, Light Blue = mild.» (`devices/m17/m17-brochure-en.md:482`). Числовые пороги — нет данных.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:474`
- **Ограничения и расхождения:** Определение влажности по поглощению УФ — утверждение производителя, не проверено (KNOWN_ISSUES) (`devices/m17/m17-brochure-en.md:478`)

### Collagen — Потеря коллагена

- **Название в аппарате (EN):** Collagen (список показателей в руководстве: `devices/m17/m17-user-manual.md:790`) · **RU:** Потеря коллагена _(перевод, не из источника)_
- **Категория (брошюра):** Anti-aging
- **Слой:** «reach the dermis»
- **Что измеряет (брошюра, маркетинг):** «The skin detector uses a cold light source system to illuminate the skin surface.» (`devices/m17/m17-brochure-en.md:490`)
- **Спектр / свет:** «cold light source system»; «absorb the ultraviolet light» (`devices/m17/m17-brochure-en.md:490`)
- **Как читать:** «The Collagen can clearly show the skin texture and collagen loss areas.» (`devices/m17/m17-brochure-en.md:494`). Числовые пороги — нет данных.
- **Связанные процедуры (брошюра):** «Anti-aging, skin rejuvenation, wrinkle removal and other projects have corresponding changes and improvements to this problem.» (`devices/m17/m17-brochure-en.md:498`) — рекомендация производителя, не протокол клиники.
- **Источник:** карточка брошюры `devices/m17/m17-brochure-en.md:484`
- **Ограничения и расхождения:** «Cold light» и «ultraviolet» в одном описании — непонятно, какой свет используется (`devices/m17/m17-brochure-en.md:490`)

## Дополнительные функции (не входят в 18 показателей)

### Sunscreen Testing — Тест солнцезащитного средства

- Брошюра: «Verification of sunscreen product effectiveness» (`devices/m17/m17-brochure-en.md:500`)

### Problem Skin (UV 365 nm) — «Проблемная кожа»: флуоресцентные агенты, свинец/ртуть, «гормональное лицо», витилиго

- Брошюра: «Fluorescent agent, lead and mercury precipitation, hormone face, vitiligo» (`devices/m17/m17-brochure-en.md:512`)
- ⚠️ Выявление свинца, ртути и витилиго — **медицинское утверждение производителя**, не диагностика (KNOWN_ISSUES). Блок продублирован в брошюре

### Aging Trend Prediction / Skin Aging — Прогноз старения («Now, 3, 5, 8, 10 Years»)

- Брошюра: «Simulate facial aging issues» (`devices/m17/m17-brochure-en.md:528`)
- Моделирование, а не измерение

### 3D Slice — 3D-срез

- Брошюра: «3 Spectrum Slices» (`devices/m17/m17-brochure-en.md:536`)

- **Руководство:** 3D Slice — п. 7.8 (`devices/m17/m17-user-manual.md:850`); Skin Aging — п. 7.9 (`devices/m17/m17-user-manual.md:861`); лупа Magnify — п. 7.7 (`devices/m17/m17-user-manual.md:837`); сравнение — п. 7.6 (`devices/m17/m17-user-manual.md:807`).

## Характеристики аппарата (для справки)

| Параметр | Руководство | Брошюра |
|---|---|---|
| ОС | `devices/m17/m17-user-manual.md:388` — Android 8.1.0 | `devices/m17/m17-brochure-en.md:629` — Android 12 ⚠️ расхождение |
| Камера | `devices/m17/m17-user-manual.md:386` — 20 million | `devices/m17/m17-brochure-en.md:21` — 20MP |
| Экран | `devices/m17/m17-user-manual.md:389` — 15.6 inch | `devices/m17/m17-brochure-en.md:42` — 15.6" |
| Память | `devices/m17/m17-user-manual.md:390` — 2GB / `devices/m17/m17-user-manual.md:391` 64GB | `devices/m17/m17-brochure-en.md:631` — 2GB / 64GB |
| Питание | `devices/m17/m17-user-manual.md:384` — 25 W, 110~230 VAC | `devices/m17/m17-brochure-en.md:626` — 25W |
