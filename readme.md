🧩 Git Manager CLI
Интерактивное консольное приложение на Python для управления локальными и удалёнными Git-репозиториями. Позволяет выполнять команды Git через удобное TUI-меню: коммиты, работа с ветками, удалёнными репозиториями, настройка конфигурации, управление .gitignore и загрузка отдельных файлов из GitHub.

📦 Возможности
📁 Работа с файлами и коммитами
git status, add, commit, diff, reset, rm, log

Автокоммит всех файлов

Откат к произвольному коммиту

Удаление файлов из последнего коммита

Сравнение изменений между коммитами

🌿 Управление ветками
Создание, удаление, переименование веток

Переключение между ветками

Слияние и откат слияния

Просмотр различий между ветками (diff, log)

Очистка устаревших удалённых веток

🌐 Работа с удалёнными репозиториями
Просмотр, добавление и удаление remote-репозиториев

git pull с поддержкой --allow-unrelated-histories

git push на указанный branch

🔍 Просмотр и загрузка отдельных файлов из GitHub без клонирования

⚙️ Инициализация и конфигурация
git init

Установка имени пользователя и email (git config)

Просмотр текущей конфигурации

📄 Управление .gitignore
Просмотр текущего .gitignore

Добавление и удаление записей

⚡ Применение шаблона .gitignore для Python

🧹 Очистка репозитория
Полный сброс истории (rm --cached, reset --hard)

Сохранение всех файлов в рабочем каталоге

🖥️ Интерфейс (пример)
markdown
Копировать
Редактировать
Результат выполнения команды:
----------------------------------------
.gitignore не найден.
----------------------------------------

Управление .gitignore:
  Просмотр .gitignore
  Добавить в .gitignore
> Применить шаблон Python
  Вернуться в главное меню
🚀 Установка и запуск
bash
Копировать
Редактировать
git clone https://github.com/yourname/git-manager-cli.git
cd git-manager-cli
pip install -r requirements.txt
python main.py
⚠️ Работает на Windows (используется msvcrt). Для Linux-версии планируется поддержка curses или prompt_toolkit.

📂 Структура проекта
bash
Копировать
Редактировать
├── main.py              # Точка входа
├── README.md
├── requirements.txt     # Зависимости
└── .gitignore           # Автоматически создаётся
🛠️ Зависимости
text
Копировать
Редактировать
colorama
requests
bash
Копировать
Редактировать
pip install colorama requests
🔭 Планы по развитию
 Кроссплатформенный ввод (prompt_toolkit)

 Шаблоны .gitignore для разных языков (C++, Node.js, Java и др.)

 Загрузка нескольких файлов из GitHub

 Логирование всех операций (log.txt)

 Выделение модулей: core/, ui/, commands/

📄 Лицензия
MIT License