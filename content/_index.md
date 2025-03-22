---
# Оставьте заголовок пустым, чтобы использовать заголовок сайта
title: Project Research Group
date: 2025-03-21
type: landing

sections:
  - block: hero
    content:
      title: |
        Математическое моделирование
        теплопроводности и горения
      image:
        filename: welcome.jpg
      text: |
        <br>
        Этот проект посвящён математическому моделированию процессов теплопроводности и детерминированного горения. 
        Используя дифференциальные уравнения и численные методы, мы анализируем различные режимы горения 
        и реализуем вычислительные эксперименты в OpenModelica и Julia.
  
  - block: collection
    content:
      title: Последние новости
      subtitle:
      text: |
        Следите за последними обновлениями нашего исследования, моделирования и результатов по теплопроводности и горению.
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        Наше исследование направлено на изучение фундаментальных аспектов теплопередачи и горения, а также применение численных методов для моделирования различных режимов.
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Последние публикации
      text: "Ознакомьтесь с нашими последними научными работами и отчётами по моделированию теплопроводности и горения."
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Познакомьтесь с нашей командой →" %}}
    design:
      columns: '1'
---
