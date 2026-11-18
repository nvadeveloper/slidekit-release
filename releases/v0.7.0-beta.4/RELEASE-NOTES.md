Slidekit 0.7 beta 4 — a desktop editor for interactive e-learning courses: slide courses and longreads. What's new since 0.7.0-beta.3.

**Download:** `.dmg` for macOS (Apple silicon or Intel), `.exe` for Windows 10/11. The installers are not signed yet — see «Installing the beta» in the README for the one-time steps.

**Why the learner cannot go on — short and plain**

- The plaque that says why «Next» or a line of the menu is closed now says what the learner sees, in one voice: «Open every step — 4 left», «Turn every card», «Answer the question to go on», «First go through “…”» (a slide's name is cut by a word at forty characters). In a longread: «First go through everything above», «First go through the previous lesson». The learner no longer reads «the block “…”».
- The plaques can be turned off: «Hints of why one cannot go on» in «Player» and in the longread's settings. What is locked stays locked, and a screen reader still says why.
- A slide's plaque is drawn inside the slide and placed within it by its size, so a menu line in a scrolling panel no longer clips it.

**Importing a page-style course**

- A SCORM package of a page-style course that was re-zipped on a Mac now brings all its pictures and videos: file names written in UTF-8 without the archive's flag are read correctly, and a «й» stored in two parts is matched too.
- Heading and subheading blocks no longer bring the template's hidden English paragraph.
- The spacing the author set above and below a block comes over; the course's usual spacing stays Slidekit's.
- A longread imported before keeps its old content — import the package again.

**Fixed:** the «Contents» button of the course master is as wide as its word and no longer breaks it in two. A menu already placed in a course keeps its width until it is placed again.

**Under the hood:** Electron 45.3.4 (Chromium 156.0.8078.100), as in beta 3.

**Note:** the course format is now v96. Courses from earlier betas open and are brought up to date; a course saved in 0.7.0-beta.4 does not open in 0.7.0-beta.3 or earlier.

**Requirements:** macOS 13 or later (Apple silicon or Intel), Windows 10/11 x64, a window at least 1280 px wide. **Guide:** Help → Guide in the app, in English and Russian.

**Known limitations**

- No automatic updates yet: install new versions by hand.
- The installers are not code-signed.
- Not yet tried on real machines — tell us how it goes: keys kept by the newer key-store methods in the macOS Keychain and in Windows; Claude Code and Codex installed with npm, nvm-windows, Volta or scoop; the policy from the Windows registry. Volta's own launchers may not be found yet.
- On Windows, recording simulations, the MP4 video, finding personal data and the system's voices have not been tried on real machines yet.
- A Rive animation shows its first frame in the editor's preview — check it with «Open in browser». Files from Rive's free plan show Rive's splash screen.
- Voice services other than the system's need your own key or your company's model.

**Feedback:** nvadeveloper@gmail.com or Help → Report a Problem or Suggest an Idea… in the app.

---

Slidekit 0.7 beta 4 — настольный редактор интерактивных курсов: слайдовых и лонгридов. Что нового с 0.7.0-beta.3.

**Скачать:** `.dmg` для macOS (Apple silicon или Intel), `.exe` для Windows 10/11. Установщики пока не подписаны — однократные шаги описаны в README, раздел «Installing the beta».

**Почему нельзя дальше — коротко и понятно**

- Плашка, которая объясняет, почему закрыты «Далее» или строка меню, теперь говорит одним голосом о том, что видит ученик: «Откройте все шаги — осталось 4», «Переверните все карточки», «Ответьте на вопрос, чтобы продолжить», «Сначала пройдите «…»» (имя слайда обрезается по слову до сорока знаков). В лонгриде — «Сначала пройдите всё, что выше», «Сначала пройдите предыдущий урок». Слов «блок «…»» ученик больше не видит.
- Плашки можно выключить: «Подсказки, почему нельзя дальше» в окне «Плеер» и в настройках лонгрида. Недоступное остаётся недоступным, а причину по-прежнему говорит экранный диктор.
- Плашка слайда рисуется внутри слайда и ставится в него по своему размеру — строка меню в панели прокрутки её больше не обрезает.

**Импорт страничного курса**

- Пакет SCORM страничного курса, пересобранный на Mac, теперь переносит все картинки и видео: имена файлов в UTF-8 без флага архива читаются правильно, буква «й», записанная из двух частей, тоже находится.
- Блоки заголовка и подзаголовка больше не приносят скрытый английский абзац шаблона.
- Отступы сверху и снизу блока, заданные автором, переносятся; обычный отступ курса остаётся отступом Slidekit.
- Лонгрид, импортированный раньше, сам не исправится — импортируйте пакет заново.

**Исправлено:** кнопка «Содержание» мастера курса шириной по слову и больше не переносит его по частям. Меню, уже поставленное в курс, сохраняет прежнюю ширину, пока его не поставят заново.

**Внутри:** Electron 45.3.4 (Chromium 156.0.8078.100), как в beta 3.

**Важно:** формат курса теперь v96. Курсы из прежних бет открываются и обновляются; курс, сохранённый в 0.7.0-beta.4, не откроется в 0.7.0-beta.3 и раньше.

**Требования:** macOS 13 и новее (Apple silicon или Intel), Windows 10/11 x64, окно не уже 1280 px. **Руководство:** «Справка → Руководство» в программе, на русском и английском.

**Известные ограничения**

- Автообновления пока нет: новые версии ставятся вручную.
- Установщики не подписаны.
- Ещё не проверено на настоящих машинах — расскажите, как пройдёт: ключи в Связке ключей macOS и в Windows с новыми методами хранилища; Claude Code и Codex, поставленные через npm, nvm-windows, Volta или scoop; политика из реестра Windows. Собственные запускатели Volta пока могут не находиться.
- На Windows запись симуляций, ролик MP4, поиск личных данных и голоса системы ещё не проверены на настоящих машинах.
- В просмотре внутри редактора анимация Rive показывает первый кадр — проверяйте её через «Открыть в браузере». Файлы с бесплатного тарифа Rive показывают заставку Rive.
- Голосовым службам, кроме системной, нужен свой ключ или модель компании.

**Обратная связь:** nvadeveloper@gmail.com или «Справка → Сообщить о проблеме или предложить идею…» в программе.
