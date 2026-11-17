Slidekit 0.7 beta — a desktop editor for interactive e-learning courses: slide courses and, new in this version, longreads. What's new since 0.6.0-beta.1.

**Download:** `.dmg` for macOS (Apple silicon or Intel), `.exe` for Windows 10/11. The installers are not signed yet — see «Installing the beta» in the README for the one-time steps.

**New: longreads, the second course format**

- **A course of lessons made of blocks**, read from top to bottom, that fits a phone by itself: tabs, processes and markers rearrange on a narrow screen. It lives in the same `.slidekit` file and exports the same way — web page, SCORM 1.2 and 2004, cmi5, xAPI. «Create a longread» on the start screen.
- **Written like an article:** Markdown as you type, «/» opens the block library. Text, lists, quotes, tables, pictures and galleries, video, sound, files, code, buttons and pop-up windows, tabs and accordions with blocks inside, a process, a timeline, markers on a picture, scenarios, sorting, embedded pages and videos, your own HTML.
- **Checks and logic:** questions, a test lesson with a passing score and attempts, surveys; variables and conditions show blocks to some learners only; light, dark or «As on the device» pages; your own CSS for the whole course.
- **The AI agent:** «Create with AI» in the longread format asks a few questions, shows a plan you can change and writes the lessons; the longread's chat changes lessons and blocks on request.
- **A course from a document:** drop a regulation or a manual (DOCX, PDF, PPTX, HTML, text) and get modules and lessons — the «Course from a document» card on the start screen or a ready request in the chat.
- «Import course…» opens a SCORM package of a page-style course (lessons of blocks) as a longread. «Recently deleted» brings back a block or a lesson removed by mistake; «Reviewer mode» collects comments on lessons and blocks.

**New: the «Animation» tab**

- Entrance, exit and emphasis effects, their options and duration on one ribbon tab; «Preview» plays them on the canvas.
- **Motion paths:** an object moves along a line, an arc, a zigzag, a circle or a path you draw — with the timeline or by the «Move along motion path» trigger; a path's points can be typed as numbers.
- **Copy animation:** take one object's animation and click the objects that should get it; «To all on the slide», «Remove animation».
- **Lottie and Rive (optional):** vector Lottie animations (`.json`, `.lottie` — exported from Figma, for example) on slides and in longreads, interactive Rive animations (`.riv`) on slides. Their players go into a course only when it has such an animation, and work offline.
- **Objects touching:** the triggers «Object intersects another» and «Object stops intersecting another» go by the visible shape — a shape's outline, a picture's opaque part — not by the frame.

**Editing several objects at once**

- The properties show what the selected objects share and «Mixed» where they differ; a new value goes to all of them in one undo step. States of several objects are edited together; «Select similar» selects every object of the same kind and look on the layer.

**AI assistants with full control**

- The slide assistant renames objects, moves them between layers, duplicates, changes triggers, variables, colours and looks, replaces pictures with files from the chat, sets up ready-made blocks, video and sound, motion paths and Lottie. The longread assistant adds buttons, embeds, markers, code, variables and conditions, and blocks inside tabs and accordions. Answer options get an explanation of why.

**A unified look**

- One tooltip with a short delay on every icon button, one colour picker, one scale of text sizes and rounding across the editor. The ribbon fits its window at any width, without scrolling.

**The course view**

- «The course view» shows the links of the slide you choose or point at; the labels on cards («→ 7.2», «+3») take you to the slides they name; «All links» shows every link at once; a collapsed scene shows its links too.

**Also on slides:** a real table object, a formula in a line of text, a hint on words, «Recipe…» for common triggers, a code editor window for HTML.

**Fixed (export review):** a longread's progress in the LMS is no longer overwritten on return; the course says «saved» only once the LMS has taken the data; the cover no longer leaves an empty bookmark; a longread's test reports to xAPI under its own name.

**Under the hood:** Electron 44.11.3 (Chromium 152.0.7977.169).

**Note:** the course format is now v94. Courses from earlier betas open in 0.7 and are brought up to date as they open; courses saved in 0.7 do not open in 0.6 or earlier.

**Requirements:** macOS 13 or later (Apple silicon or Intel), Windows 10/11 x64, a window at least 1280 px wide. **Guide:** Help → Guide in the app, in English and Russian.

**Known limitations**

- No automatic updates yet: install new versions by hand.
- The installers are not code-signed.
- A Rive animation shows its first frame in the editor's preview — check it with «Open in browser». Files from Rive's free plan show Rive's splash screen.
- On Windows, recording simulations, the MP4 video, finding personal data and the system's voices have not been tried on real machines yet — tell us how it goes.
- Voice services other than the system's need your own key or your company's model.

**Feedback:** nvadeveloper@gmail.com or Help → Report a Problem or Suggest an Idea… in the app.

---

Slidekit 0.7 beta — настольный редактор интерактивных курсов: слайдовых и, впервые в этой версии, лонгридов. Что нового с 0.6.0-beta.1.

**Скачать:** `.dmg` для macOS (Apple silicon или Intel), `.exe` для Windows 10/11. Установщики пока не подписаны — однократные шаги описаны в README, раздел «Installing the beta».

**Новое: лонгриды — второй формат курса**

- **Курс из уроков, собранных из блоков,** читается сверху вниз и сам подстраивается под телефон: вкладки, процесс и маркеры перестраиваются на узком экране. Хранится в том же файле `.slidekit` и выгружается так же — веб-страница, SCORM 1.2 и 2004, cmi5, xAPI. «Создать лонгрид» на стартовом экране.
- **Пишется как статья:** Markdown при наборе, «/» открывает библиотеку блоков. Текст, списки, цитаты, таблицы, картинки и галереи, видео, звук, файлы, код, кнопки и всплывающие окна, вкладки и аккордеоны с блоками внутри, процесс, хронология, маркеры на картинке, сценарии, сортировка, встроенные страницы и видео, свой HTML.
- **Проверка и логика:** вопросы, урок-тест с проходным баллом и попытками, опросы; переменные и условия показывают блоки только части учеников; светлые, тёмные или «Как на устройстве» страницы; свой CSS для всего курса.
- **ИИ-агент:** «Создать с ИИ» в формате лонгрида задаёт несколько вопросов, показывает план, который можно поправить, и пишет уроки; чат лонгрида меняет уроки и блоки по просьбе.
- **Курс из документа:** перетащите регламент или инструкцию (DOCX, PDF, PPTX, HTML, текст) — и получите модули и уроки: карточка «Курс из документа» на стартовом экране или готовый запрос в чате.
- «Импорт курса…» открывает пакет SCORM страничного курса (уроки из блоков) лонгридом. «Недавно удалённое» возвращает блок или урок, удалённый по ошибке; «Режим проверяющего» собирает замечания к урокам и блокам.

**Новое: вкладка «Анимация»**

- Появление, исчезновение и выделение, их параметры и длительность — на одной вкладке ленты; «Просмотр» проигрывает их на холсте.
- **Траектории движения:** объект движется по линии, дуге, зигзагу, кругу или нарисованному вами пути — вместе с таймлайном или по триггеру «Двигать по траектории»; точки пути можно задать числами.
- **Копировать анимацию:** возьмите анимацию одного объекта и щёлкайте объекты, которым её дать; «Ко всем на слайде», «Удалить анимацию».
- **Lottie и Rive (дополнительно):** векторные анимации Lottie (`.json`, `.lottie` — например, выгруженные из Figma) на слайдах и в лонгридах, интерактивные анимации Rive (`.riv`) на слайдах. Их проигрыватели попадают в курс, только если в нём есть такая анимация, и работают без интернета.
- **Касание объектов:** триггеры «Объект касается другого» и «Объект перестаёт касаться другого» учитывают видимую форму — контур фигуры, непрозрачную часть картинки, — а не рамку.

**Правка нескольких объектов сразу**

- Свойства показывают общее у выбранных объектов и «Разные», где значения отличаются; новое значение получают все одним шагом отмены. Состояния нескольких объектов правятся вместе; «Выделить похожие» выбирает все объекты того же вида и оформления на слое.

**ИИ-ассистенты с полным контролем**

- Ассистент слайдов переименовывает объекты, переносит их между слоями, дублирует, меняет триггеры, переменные, цвета и оформление, заменяет картинки файлами из чата, настраивает готовые блоки, видео и звук, траектории и Lottie. Ассистент лонгрида добавляет кнопки, встраивание, маркеры, код, переменные и условия, блоки внутри вкладок и аккордеонов. У вариантов ответа — пояснение, почему так.

**Единый вид**

- Одна подсказка с короткой задержкой у каждой кнопки-значка, один выбор цвета, одна шкала размеров текста и скруглений во всём редакторе. Лента помещается в окно любой ширины без прокрутки.

**Вид курса**

- «Вид курса» показывает связи выбранного слайда или слайда под указателем; метки на карточках («→ 7.2», «+3») ведут к слайдам, которые называют; «Все переходы» показывает все связи сразу; свёрнутая сцена тоже показывает свои связи.

**Ещё на слайдах:** настоящая таблица, формула в строке текста, подсказка к словам, «Рецепт…» для частых триггеров, окно редактора кода для HTML.

**Исправлено (проверка экспорта):** прогресс лонгрида в LMS больше не затирается при возвращении; курс пишет «сохранено», только когда LMS приняла данные; обложка не оставляет пустую закладку; тест лонгрида отправляется в xAPI под своим именем.

**Внутри:** Electron 44.11.3 (Chromium 152.0.7977.169).

**Важно:** формат курса теперь v94. Курсы из прежних бет открываются в 0.7 и обновляются при открытии; курсы, сохранённые в 0.7, в 0.6 и раньше не открываются.

**Требования:** macOS 13 и новее (Apple silicon или Intel), Windows 10/11 x64, окно не уже 1280 px. **Руководство:** «Справка → Руководство» в программе, на русском и английском.

**Известные ограничения**

- Автообновления пока нет: новые версии ставятся вручную.
- Установщики не подписаны.
- В просмотре внутри редактора анимация Rive показывает первый кадр — проверяйте её через «Открыть в браузере». Файлы с бесплатного тарифа Rive показывают заставку Rive.
- На Windows запись симуляций, ролик MP4, поиск личных данных и голоса системы ещё не проверены на настоящих машинах — расскажите, как пройдёт.
- Голосовым службам, кроме системной, нужен свой ключ или модель компании.

**Обратная связь:** nvadeveloper@gmail.com или «Справка → Сообщить о проблеме или предложить идею…» в программе.
