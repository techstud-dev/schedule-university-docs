
<div align="center">
  <br>
  <img src="source/logo-dev.png" alt="">
  <h1>techstud.dev</h1>
</div>

URL деплоя: [Not active](https://mrnikamilon.github.io/obsidian-quartz-nikamilon-template)

> Шаблон для размещения вашего блокнота Obsidian на страницах GitHub с развертыванием CI.
### 🛠  Технический стек
1. **Hugo**:
	* Статический генератор сайтов, который преобразует Markdown-файлы в HTML.
    - Быстрый и гибкий, поддерживает множество тем и плагинов.
        
2. **Go (Golang)**:
    - Язык программирования, на котором написан Hugo.
    - Обеспечивает высокую производительность Quartz.
        
3. **Markdown**:
    - Формат хранения заметок.
    - Поддерживает ссылки, изображения, таблицы, код и другие элементы.
        
4. **Graphviz**:
    - Инструмент для визуализации графов (например, для отображения связей между заметками).
        
5. **Git**:
    - Используется для управления версиями и публикации изменений.
    - Позволяет синхронизировать заметки между устройствами.
        
6. **GitHub/GitLab Pages**:
    - Хостинг для статических сайтов.
    - Quartz можно легко развернуть на GitHub Pages или GitLab Pages.
        
7. **Obsidian (опционально)**:
    - Редактор для работы с Markdown-файлами.
    - Поддерживает графы, теги и другие функции для организации заметок.
###  🌐  О платформе
Данная платформа необходима для хранения документации и заметок по проектам TechStud. Платформа работает на проекте Quartz 4.0 и деплоится с помощью [GitHub](https://github.com/features/actions) Actions на [GitHub Pages](https://pages.github.com/) (*рекомендую вам ознакомится с этими технологиями*).

### 🧑‍💻 Как начать работать с платформой
* Для начала необходимо установить Obsidian и разобраться бегло с ним, линк для установки: [Download Obsidian](https://obsidian.md/download)

* После этого нужно сгенерировать божий ключ в GitHub находится он по адресу **Settings** → **Developer settings** → **Personal access tokens** → **Tokens**

* Поставьте галочки так же как и показано на скрине и нажмите кнопку Generate token

* Сохраните его себе, GitHub не дает просмотреть свой токен только повторно сгенерировать. 

* Теперь вам нужно склонировать репозиторий себе на локальную машину(рекомендую делать это в папку где лежат ваши волты Obsidian)

* Теперь создайте новый волт как показано на скрине, и укажите такой адрес: */путь_до_репозитория/category-folder*

* Нажмите доверять.

* Теперь вы можете вносить изменения в волте и они автоматически будут мигрировать в удаленный репозиторий и автоматически деполоится.

###  😍 Пользователи
* Редактор: [@artem-xopc](https://github.com/artem-xopc)
* Ответственный за платформу: [@MrNikaMilon](https://github.com/MrNikaMilon)
 
🔐 **Попросить доступ**:
* [@artem-xopc](https://github.com/artem-xopc)

### 👍 Информация и полезные материалы
* Подробный туториал: [**Host your Obsidian notebook on GitHub Pages for free**](https://dev.to/defenderofbasic/host-your-obsidian-notebook-on-github-pages-for-free-8l1)
* Оригинальный репозиторий: [**obsidian-quartz-template**](https://github.com/DefenderOfBasic/obsidian-quartz-template)
* Шоукейс пример: [**Quartz Showcase**](https://quartz.jzhao.xyz/showcase)
