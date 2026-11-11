# Лабораторна робота: Linux Fundamentals та Bash Scripting

## Що було зроблено (Хід виконання роботи)

### 1. Інтерактивні курси KillerCoda
Пройдено практичні туторіали з основ та адміністрування Linux:
* [Linux Fundamentals](https://killercoda.com/online-marathon/course/DevOps_I/Linux_fundamentals)
* [Linux Basics Administration](https://killercoda.com/online-marathon/course/DevOps_I/Linux_basics_adm)

**Скриншоти проходження курсів (Google Drive):**
* [Скриншот 1](https://drive.google.com/file/d/19peuxtwT9ryGndjbafQhkzCzc2ISHmvr/view?usp=sharing)
* [Скриншот 2](https://drive.google.com/file/d/1RfVcWPgnvk01oWoTJRMivsmYhleadZ8g/view?usp=sharing)
* [Скриншот 3](https://drive.google.com/file/d/19peuxtwT9ryGndjbafQhkzCzc2ISHmvr/view?usp=sharing) *(або ваше третє посилання)*

---

### 2. Адміністрування ОС Linux (Віртуальне середовище)
* **Створення користувача та групи:** Створено нового користувача `borys`, додано його до групи `root` та виконано вхід під цим користувачем:
  ```bash
  sudo useradd -m -s /bin/bash borys
  sudo usermod -aG root borys
  su - borys