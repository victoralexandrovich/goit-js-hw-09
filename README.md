# GoIT JS Homework 09 - Vite, SimpleLightbox & Local Storage

JavaScript homework assignment for the GoIT course (Module 9). Topic: modern
project bundling with Vite, multipage structure, integrating the
`SimpleLightbox` library via npm, and working with `localStorage` for form state
persistence.

**What was done:**

- Set up the repository `goit-js-hw-09` using Vite and structured the project
  with a multipage setup (`index.html`, `1-gallery.html`, `2-form.html`)
- **Task 1 (Image Gallery with SimpleLightbox):** Refactored the previous
  gallery implementation by removing manual event delegation and integrating
  `SimpleLightbox` via npm, configuring options for captions and animation
  delays (`captionDelay: 250`)
- **Task 2 (Feedback Form & Local Storage):** Implemented a feedback form script
  that dynamically tracks input changes via delegation, saves form state into
  `localStorage` using the key `"feedback-form-state"`, restores data on page
  load, and validates fields upon submission
- Verified code formatting with Prettier and ensured zero errors or warnings in
  the browser console across all tasks via GitHub Pages

---

# Домашнє завдання 09 GoIT JS — Vite, SimpleLightbox та Local Storage

Практичне завдання з курсу JavaScript від GoIT (Модуль 9). Тема: сучасне
збирання проєктів за допомогою Vite, багатосторінкова структура, інтеграція
бібліотеки `SimpleLightbox` через npm та збереження стану форм у `localStorage`.

**Що зроблено:**

- Створено репозиторій `goit-js-hw-09` на базі збірки Vite із налаштуванням
  багатосторінкової архітектури (`index.html`, `1-gallery.html`, `2-form.html`)
- **Задача 1 (Галерея зображень із SimpleLightbox):** Здійснено рефакторинг
  галереї з видаленням власного делегування та підключенням бібліотеки
  `SimpleLightbox` через npm, додано налаштування підписів з затримкою появи
  (`captionDelay: 250`)
- **Задача 2 (Форма зворотного зв'язку):** Реалізовано скрипт форми з
  відстеженням події `input`, автоматичним збереженням даних в `localStorage`
  під ключем `"feedback-form-state"`, відновленням даних при завантаженні та
  валідацією наявності всіх заповнених полів під час сабміту
- Перевірено форматування коду за допомогою Prettier, а також відсутність
  будь-яких помилок чи попереджень у консолі на живій сторінці GitHub Pages
