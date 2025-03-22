---
title: "Математическое моделирование теплопроводности и горения: Этап 1 — Теоретическая модель"
authors:
- admin
- Irina
- Milena
- Evgenia
- Maria
date: "2025-03-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-14T00:00:00Z"

# Тип публикации
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Теоретическое описание модели теплопроводности и детерминированного горения"
publication_short: "Модель горения"

abstract: |
  В данном этапе проекта рассматривается математическая модель теплопроводности с экзотермической химической реакцией. 
  Представлено теоретическое описание процесса горения с учётом теплопередачи и закона Аррениуса. 
  Разработаны основные уравнения системы и проведён переход к безразмерным переменным.

# Краткое описание (аннотация)
summary: "Формулировка математической модели теплопроводности и детерминированного горения. Определены основные уравнения и параметры системы."

tags:
- Теплопроводность
- Горение
- Математическое моделирование
- Дифференциальные уравнения
- Закон Аррениуса

featured: false

links:
- name: GitHub репозиторий
  url: https://github.com/Nelagorean/project_site

# Удаляем неактуальные ссылки
url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named featured.jpg/png to your page's folder. 
image:
  caption: 'Схема распространения волны горения'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. internal-project references content/project/internal-project/index.md.
#   Otherwise, set projects: [].
projects:
- project_heat_conduction

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. slides: "example" references content/slides/example/index.md.
#   Otherwise, set slides: "".
slides: ""
---

## Введение
Горение — сложный физико-химический процесс, включающий теплопроводность и экзотермическую реакцию. Для его описания используется система дифференциальных уравнений, учитывающая закон Аррениуса.

## Математическая модель

### Основные уравнения
#### Уравнение теплопроводности с учётом энерговыделения:
$$
\rho c \frac{\partial T}{\partial t} = \kappa \frac{\partial^2 T}{\partial x^2} - \rho Q \frac{\partial N}{\partial t}
$$

#### Уравнение химической реакции (закон Аррениуса):
$$
\frac{\partial N}{\partial t} = - \frac{N}{\tau} e^{-E/RT}
$$

### Безразмерные переменные
- Температура: $\tilde{T} = \frac{cT}{Q}$
- Энергия активации: $\tilde{E} = \frac{cE}{RQ}$
- Новая система уравнений:
$$
\frac{\partial T}{\partial t} = \chi \frac{\partial^2 T}{\partial x^2} - \frac{\partial N}{\partial t}
$$
$$
\frac{\partial N}{\partial t} = - \frac{N}{\tau} e^{-E/T}
$$

## Заключение
Первый этап проекта включает формулировку математической модели горения и теплопроводности. Полученные уравнения будут использоваться в дальнейшем для численного моделирования различных режимов горения. 

{{% callout note %}}
Следующий этап проекта будет посвящён разработке алгоритмов численного решения модели.
{{% /callout %}}
