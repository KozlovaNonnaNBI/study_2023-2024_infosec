---
## Front matter
lang: ru-RU
title: Индивидуальный проект
subtitle: Первый этап
author:
  - Козлова Нонна
institute:
  - Российский университет дружбы народов, Москва, Россия
  - НБИбд-01-22
date: 01 января 1970

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Вводная часть

## Материалы и методы

- Процессор `pandoc` для входного формата Markdown
- Результирующие форматы
	- `pdf`
	- `html`
- Автоматизация процесса создания: `Makefile`

# Создание презентации

## Процессор `pandoc`

- Pandoc: преобразователь текстовых файлов
- Сайт: <https://pandoc.org/>
- Репозиторий: <https://github.com/jgm/pandoc>

## Формат `pdf`

- Использование LaTeX
- Пакет для презентации: [beamer](https://ctan.org/pkg/beamer)
- Тема оформления: `metropolis`

## Код для формата `pdf`

```yaml
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
```

## Формат `html`

- Используется фреймворк [reveal.js](https://revealjs.com/)
- Используется [тема](https://revealjs.com/themes/) `beige`

## Код для формата `html`

- Тема задаётся в файле `Makefile`

```make
REVEALJS_THEME = beige 
```
# Презентация

## Цель

Установить Kali Linux

## Скачала файл


![Сайт kali.org](image/1.png){#fig:001 width=70%}

## Использовав кнопку "Добавить" в виртуальной машине, запустила kali

![При установке ввела логин и пароль по умолчанию (kali/kali)](image/2.png){#fig:002 width=70%}

## Вывод

В ходе первого этапа индивидуального проекта я успешно установила Kali Linux.

:::

