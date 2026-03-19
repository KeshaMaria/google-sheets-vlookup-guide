# Google Sheets VLOOKUP Guide / Гид по ВПР в Google Таблицах

[![Русский](https://img.shields.io/badge/lang-ru-blue.svg)](ru/00-index.md)
[![English](https://img.shields.io/badge/lang-en-red.svg)](en/00-index.md)

A step-by-step guide to creating a smart VLOOKUP with category selection and error handling in Google Sheets.  
Пошаговое руководство по созданию умного ВПР с выбором категории и обработкой ошибок в Google Таблицах.

---

## 📚 About the project / О проекте

**English**  
This guide demonstrates how to combine VLOOKUP, IF, and IFERROR functions to automatically fetch prices based on product type (retail/wholesale) and handle missing products gracefully. The guide is available in two languages: Russian and English.

**Русский**  
В этом руководстве показано, как комбинировать функции ВПР, ЕСЛИ и ЕСЛИОШИБКА для автоматического подбора цен в зависимости от типа товара (розница/опт) и корректной обработки отсутствующих товаров. Руководство доступно на двух языках: русском и английском.

---

## 📁 Project structure / Структура проекта

```
google-sheets-vlookup-guide
│
├── README.md                 # This file / Этот файл
│
├── ru                        # Russian version / Русская версия
│   ├── 00-index.md           # Introduction and task / Введение и задача
│   ├── 01-vlookup.md         # Step 1: VLOOKUP / Этап 1: ВПР
│   ├── 02-if.md              # Step 2: IF / Этап 2: ЕСЛИ
│   ├── 03-iferror.md         # Step 3: IFERROR / Этап 3: ЕСЛИОШИБКА
│   ├── 04-result.md          # Final result / Результат
│   └── images                # Screenshots for Russian version
│       ├── 00-difficulty-level.png
│       ├── 01-orders-table.png
│       ├── 02-price-list-table.png
│       ├── 03-step1-vlookup.png
│       ├── 04-step2-if.png
│       └── 05-final-result.png
│
└── en                        # English version / Английская версия
    ├── 00-index.md           # Introduction and task
    ├── 01-vlookup.md         # Step 1: VLOOKUP
    ├── 02-if.md              # Step 2: IF
    ├── 03-iferror.md         # Step 3: IFERROR
    ├── 04-result.md          # Final result
    └── images                # Screenshots for English version
        ├── 00-difficulty-level.png
        ├── 01-orders-table.png
        ├── 02-price-list-table.png
        ├── 03-step1-vlookup.png
        ├── 04-step2-if.png
        └── 05-final-result.png
```

---

## 🚀 How to use / Как использовать

### English
1. Clone this repository:  
   `git clone https://github.com/KeshaMaria/google-sheets-vlookup-guide.git`
2. Open any `.md` file in VS Code or any Markdown editor.
3. In VS Code, press `Ctrl+Shift+V` to preview the formatted document.
4. Navigate to `en/00-index.md` for the English version or `ru/00-index.md` for the Russian version.

### Русский
1. Склонируйте репозиторий:  
   `git clone https://github.com/KeshaMaria/google-sheets-vlookup-guide.git`
2. Откройте любой `.md` файл в VS Code или любом редакторе Markdown.
3. В VS Code нажмите `Ctrl+Shift+V` для предпросмотра.
4. Для русской версии откройте `ru/00-index.md`, для английской — `en/00-index.md`.

---

## 🛠️ Built with / Использованные инструменты

- Markdown — documentation format
- Git — version control
- GitHub — code hosting
- Visual Studio Code — recommended editor
- Google Sheets — source of examples

---

## 📄 License / Лицензия

This project is open source and available under the [MIT License](LICENSE).  
Проект с открытым исходным кодом, доступен под лицензией MIT.

---

## ✨ Author / Автор

Мария Лубенцова  
https://github.com/KeshaMaria