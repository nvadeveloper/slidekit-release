Slidekit 0.4 beta — a desktop editor for interactive slide-based e-learning courses. What's new since 0.3.0-beta.1.

**Download:** `.dmg` for macOS (Apple silicon or Intel), `.exe` for Windows 10/11. The installers are not signed yet — see «Installing the beta» in the README for the one-time steps.

**New: software simulations**

- **Record your work in any program:** Blocks → Scenarios → «Record a simulation…». Choose a screen or a window and press «Start recording». Slidekit steps aside, a small panel counts down and shows the time, and every click, typed text and key combination becomes a step with a screenshot taken just before it.
- **Review the recording:** delete steps, merge neighbours, move the place to click, pick another frame, blur passwords and personal data, write captions. The AI assistant can caption the steps from their screenshots and suggest which ones look accidental — you decide.
- **Build the course:** a demonstration (the place lit, the hint shown; it waits for a click or goes on by itself), a practice (the learner clicks, a miss says «Try again», the hint comes back on request) and a quiz (mistakes counted, the score goes to the LMS). The slides are ordinary slides you can edit; building again with other settings keeps the ones you changed.
- **Try it:** the «Try it yourself» section on our site is a simulation made exactly this way.

**Also new**

- **Exercises in code:** the assistant writes an interactive exercise in HTML, CSS and JavaScript when the course's own objects cannot make it — lines between pairs, sorting onto a picture, a small simulator. The exercise tells the course how the learner did, and the course's own layers show «Correct» or «Try again».
- **HTML fragments** with scripts read and set the course variables you tick: `slidekit.get`, `slidekit.set`, `slidekit.on`.
- **Fixes:** a variable used only by a fragment or as the course's score is no longer taken for unused; the resources library counts the recordings' screenshots; a dozen smaller fixes found in review.

**Note:** courses saved in 0.4 use course format v28 and do not open in 0.3. Courses from 0.3 open in 0.4 as they are. Recordings stay in the course file and never go into the learner's package.

**Requirements:** macOS 13 or later (Apple silicon or Intel), Windows 10/11 x64, a window at least 1280 px wide. Recording on a Mac asks once for «Screen Recording» and «Input Monitoring»; without the latter a step is taken with ⌘⌥⇧S. **Guide:** Help → Guide in the app, in English and Russian.

**Known limitations**

- No automatic updates yet: install new versions by hand.
- The installers are not code-signed. On a Mac, an unsigned app may have to be given the recording permissions again after an update.
- Recording simulations on Windows has not been tried on real machines yet — tell us how it goes.
- Not imported yet from `.story` and SCORM: motion paths, web objects, video and sound from SCORM packages, JavaScript triggers.
- Checked in SCORM Cloud so far; tell us how it works in your LMS.

**Feedback:** nvadeveloper@gmail.com or Help → Report a Problem or Suggest an Idea… in the app.

---

Бета Slidekit 0.4 — настольный редактор интерактивных слайдовых курсов. Что нового с 0.3.0-beta.1.

**Скачать:** `.dmg` для macOS (Apple silicon или Intel), `.exe` для Windows 10/11. Установщики пока не подписаны — однократные шаги описаны в README, раздел «Installing the beta».

**Новое: симуляции программ**

- **Запись работы в любой программе:** «Блоки → Сценарии → Записать симуляцию…». Выберите экран или окно и нажмите «Начать запись». Slidekit уходит с экрана, небольшая панель отсчитывает три секунды и показывает время, а каждый щелчок, набранный текст и сочетание клавиш становятся шагом со снимком экрана перед ним.
- **Разбор записи:** удалите лишние шаги, объедините соседние, подвиньте место щелчка, выберите другой кадр, размойте пароли и личные данные, подпишите шаги. ИИ-помощник может подписать шаги по снимкам и предложить, какие похожи на случайные, — решаете вы.
- **Сборка курса:** демонстрация (место подсвечено, подсказка показана; ждёт щелчка или листает сама), тренировка (ученик щёлкает сам, промах — «Попробуйте ещё раз», подсказку можно вернуть) и тест (ошибки считаются, балл уходит в LMS). Слайды — обычные, их можно править; пересборка с другими настройками не трогает те, что вы изменили.
- **Попробовать:** раздел «Попробуйте сами» на нашем сайте — симуляция, сделанная именно так.

**Ещё новое**

- **Упражнения на коде:** ассистент пишет интерактивное упражнение на HTML, CSS и JavaScript, когда объектами курса его не собрать, — соединить пары линиями, разложить по картинке, небольшой тренажёр. Упражнение сообщает курсу, как ответил ученик, а «Верно» или «Попробуйте ещё раз» показывают слои курса.
- **HTML-фрагменты** со сценариями читают и меняют отмеченные переменные курса: `slidekit.get`, `slidekit.set`, `slidekit.on`.
- **Исправления:** переменная, которую использует только фрагмент или балл курса, больше не считается неиспользуемой; библиотека ресурсов учитывает снимки записей; ещё десяток мелочей, найденных на ревью.

**Важно:** курсы, сохранённые в 0.4, записаны в формате v28 и в 0.3 не открываются. Курсы из 0.3 открываются в 0.4 как есть. Записи хранятся в файле курса и в пакет ученика не попадают.

**Требования:** macOS 13 или новее (Apple silicon или Intel), Windows 10/11 x64, окно от 1280 px в ширину. Запись на Mac один раз спрашивает «Запись экрана» и «Мониторинг ввода»; без второго шаг снимается сочетанием ⌘⌥⇧S. **Руководство:** «Справка → Руководство» в программе, на русском и английском.

**Известные ограничения**

- Обновления пока не устанавливаются сами: новые версии ставьте вручную.
- Установщики не подписаны. На Mac неподписанной программе после обновления, возможно, придётся заново дать разрешения на запись.
- Запись симуляций на Windows ещё не проверялась на настоящих машинах — расскажите, как пройдёт.
- Из `.story` и SCORM пока не переносятся: траектории движения, веб-объекты, видео и звук из пакетов SCORM, триггеры с JavaScript.
- Пока проверено в SCORM Cloud; расскажите, как курс работает в вашей LMS.

**Обратная связь:** nvadeveloper@gmail.com или «Справка → Сообщить о проблеме или предложить идею…» в программе.
