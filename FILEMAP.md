# FILEMAP — старое имя → новое имя

Правило переименования: латиница (транслитерация русских слов), нижний регистр, `-` вместо пробелов и `_`. Убраны `★`, скобки, `&`, `+`, `[112558]`, суффиксы `(1)`, апострофы. Ошибки в авторах, которые были в исходных именах, **сохранены в транслитерации** (опечатка «косметтология» исправлена в задании 4) и вынесены в вопросы к клинике (`QUESTIONS.md`). Исходное имя прайса было записано в Unicode NFD («Й» = «И» + U+0306); новое имя — ASCII, то есть заведомо NFC.

| Старое имя | Новое имя | Что это |
|---|---|---|
| `M17 User Manual.md` | `devices/m17/m17-user-manual.md` | Руководство пользователя анализатора кожи M17 (EN, OCR, 16 стр. PDF) |
| `M17_Brochure_EN.md` | `devices/m17/m17-brochure-en.md` | Рекламная брошюра M17: спектры, 18 показателей, облако, характеристики (EN) |
| `HydroPeptide-Training-Guide---2024 (1).md` | `brands/hydropeptide/hydropeptide-training-guide-2024.md` | Тренинговый гайд HydroPeptide 2024: технологии, линейки, продукты (EN) |
| `HydroPeptide-Training-Guide---2024 (1) (1).md` | — **удалён** | Побайтная копия предыдущего файла (одинаковая MD5) |
| `HydroPeptide_методичка.md` | `brands/hydropeptide/hydropeptide-metodichka.md` | Русская методичка HydroPeptide: бренд, пептиды, продукты, процедуры, сочетание с аппаратами (74 стр. PDF) |
| `методичка с протоколами.md` | `brands/hydropeptide/metodichka-s-protokolami.md` | Вторая русская методичка HydroPeptide: продукты с объёмами, 12 протоколов, правила проведения (85 стр. PDF) |
| `HydroPeptide Refueling Men's Facial.md` | `brands/hydropeptide/hydropeptide-refueling-mens-facial.md` | Протокол мужского ухода Re-Fueling Men's Facial (EN, OCR, 1 стр.) |
| `Esthetics Guide_Updates_2019_rassylka[112558].md` | `brands/hydropeptide/esthetics-guide-updates-2019-rassylka.md` | Русский перевод Esthetics Guide HydroPeptide 2019: протоколы, тело, маникюр, анкеты (64 стр. PDF) |
| `41012 professional catalogue mdcomplex Exosomes.md` | `brands/mdcomplex/41012-professional-catalogue-mdcomplex-exosomes.md` | Лист каталога md:complex GenX Regen Exosomes & Polynucleotides (EN) |
| `mdcomplex Exosomes&Polynucleotides TECHNICAL DOSSIER.md` | `brands/mdcomplex/mdcomplex-exosomes-polynucleotides-technical-dossier.md` | Техническое досье того же продукта (EN) |
| `md_complex+peel+GenX_A5_web.md` | `brands/mdcomplex/md-complex-peel-genx-a5-web.md` | Каталог md:complex, md:peel, md:ceuticals для РФ (RU) |
| `★ ★ ★ DERMATHEY ПРАЙС 2026_АППАРАТЫ_УХОД.md` | `clinic/dermathey-prays-2026-apparaty-ukhod.md` | Прайс клиники DERMATHEY 2026: аппараты, уход. **Структура восстановлена**, цены не менялись |
| `Аппаратная косметология учебник.md` | `textbooks/apparatnaya-kosmetologiya-uchebnik.md` | Федотов В.П., Корецкая Е.Ю. и др. «Аппаратная косметология», Запорожье, 2013 |
| `Бочарова_Основы_практ_косметологии.md` | `textbooks/bocharova-osnovy-prakt-kosmetologii.md` | Федотов В.П., Бочаров В.А., Корецкая Е.Ю. и др. «Основы практической косметологии», 2016 (в имени — «Бочарова», см. вопросы) |
| `Новая_косметтология_1_том_Марголина.md` | `textbooks/novaya-kosmetologiya-1-tom-margolina.md` | Марголина А.А., Эрнандес Е.И. «Новая косметология», т. I, 2005 (опечатка «косметтология» из исходного имени исправлена в задании 4: было `textbooks/novaya-kosmettologiya-1-tom-margolina.md`) |
| `Новая_косметология_2_том_Марголина.md` | `textbooks/novaya-kosmetologiya-2-tom-margolina.md` | «Новая косметология», т. II, под ред. Е.И. Эрнандес, 2007 (в имени — «Марголина», см. вопросы) |

Служебные файлы: `INDEX.md` (карта репозитория), `README.md` (обзор и найденные проблемы), `FILEMAP.md` (этот файл), `QUESTIONS.md` (вопросы к клинике), `rules/KNOWN_ISSUES.md` (таблица проблем, перенесена из корня), `rules/source-hierarchy.md` (уровни доверия), `knowledge/*.md` (база знаний).
