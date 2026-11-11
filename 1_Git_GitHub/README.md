# DevOps Task: Інтеграція GitHub Actions та Git Fundamentals

## Що було зроблено (Хід виконання роботи)

### 1. Налаштування шаблону та репозиторію
* Успішно створено та налаштовано репозиторій на основі шаблону [Practical-DevOps-GitHub/github-task](https://github.com/Practical-DevOps-GitHub/github-task).
* Підключено автоматизоване тестування для перевірки виконання завдань безпосередньо в середовищі GitHub.

---

### 2. Конфігурація GitHub Actions та безпеки (PAT)
Для забезпечення проходження автоматичних тестів та надання необхідних прав доступу пайплайнам:
* **Створення Personal Access Token (PAT):** Згенеровано токен доступу у профілю GitHub із наданням таких розширених прав:
  * `Full control` of private repositories (`repo`)
  * `Full control` of orgs and teams (`admin:org`)
  * `Read and write` org projects (`project`)
* **Додавання секрету:** Створений токен безпечно збережено у вкладці репозиторію **Settings -> Secrets and variables -> Actions** під назвою `PAT`.
* **Автоматизація:** Налаштовано та перевірено роботу GitHub Actions для автоматичного запуску пайплайнів та тестів.

---

### 3. Проходження інтерактивного курсу KillerCoda
* Пройдено практичний курс з управління версіями та роботи з репозиторіями: [KillerCoda — Git Fundamentals](https://killercoda.com/pawelpiwosz/course/gitFundamentals).

---

## Результати виконання та посилання

* **GitHub репозиторій:** [https://github.com/borisme78/github-task](https://github.com/borisme78/github-task)
* **Скриншоти виконання (Google Drive):** [Переглянути скриншоти](https://drive.google.com/file/d/1zvc3TEEAcOTBfGsDapXB3-0w5L_VCZm9/view?usp=drive_link)