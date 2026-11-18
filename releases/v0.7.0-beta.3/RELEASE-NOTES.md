Slidekit 0.7 beta 3 — a desktop editor for interactive e-learning courses: slide courses and longreads. What's new since 0.7.0-beta.2.

**Download:** `.dmg` for macOS (Apple silicon or Intel), `.exe` for Windows 10/11. The installers are not signed yet — see «Installing the beta» in the README for the one-time steps.

**Captions, edited in the editor**

- «Edit captions…» in a video's or a sound's properties (or «Write captions…» when there are none) opens a window to edit them as the media plays: a cue clicked is heard from its start; its start and end are set where the media is or moved by keys; cues are split, merged, added and deleted, with an undo of the window's own. The captions show on the video as the learner will see them; «Save file…» saves them as WebVTT or SubRip.

**Markers open a bubble by the point**

- A point of «Markers on a picture» — on a slide and in a longread — opens its words in a bubble beside it, not in a panel or a window over a darkened page. The arrow keys go from point to point, Escape closes it. Courses made before get the bubble too.
- On a phone held upright, a slide's bubble stands in the empty band under the slide, with a line to its point, so the whole slide stays in sight.

**The AI assistant checks its work**

- Code the assistant writes — an exercise in code, an HTML object, a longread's code block — is tried before it goes in, and an exercise is played by the course's own engine: «correct» and «incorrect» must show the course's answer. What fails goes back to the assistant once to fix; what still fails is left out, and the chat says why.
- The chat says what a reply changes — slides and lessons, words before and after, looks, triggers, variables, the theme. A reply of more than eight changes waits for «Apply» or «Decline»; a smaller one goes in at once, «What changed» under it.

**PowerPoint import**

- A presentation with a damaged or very large video, or pictures linked to outside files, now comes in: its slides, text and pictures, without its video and sound. The note says what was left out and why.

**For the IT department**

- The company model's policy can be set by Group Policy in the Windows registry (`HKLM` or `HKCU\SOFTWARE\Policies\Slidekit\AI`), the same fields as the policy file; the registry wins over the file.
- Claude Code and Codex installed with npm on Windows are found — npm's own folder, nvm-windows, Volta, scoop — even when installed after you signed in.
- Keys of the company model and the voice services are kept by the system's newer key-store methods; keys saved before carry over.

**Names:** the «Pictures» block is now «Carousel» («Picture carousel»), «On a picture» — «Markers on a picture»; a longread's «Careful» note is «Attention» (a screen reader says so too).

**Fixed:** the focus ring of a marker's bubble shows in Firefox.

**Under the hood:** Electron 45.3.4 (Chromium 156.0.8078.100), as in beta 2.

**Note:** the course format stays v95: courses open in 0.7.0-beta.2 and 0.7.0-beta.3 alike; courses from earlier betas open and are brought up to date.

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

Slidekit 0.7 beta 3 — настольный редактор интерактивных курсов: слайдовых и лонгридов. Что нового с 0.7.0-beta.2.

**Скачать:** `.dmg` для macOS (Apple silicon или Intel), `.exe` для Windows 10/11. Установщики пока не подписаны — однократные шаги описаны в README, раздел «Installing the beta».

**Субтитры — правка в редакторе**

- «Править субтитры…» в свойствах видео или звука (или «Написать субтитры…», если их нет) открывает окно правки под воспроизведение: щелчок по реплике проигрывает её с начала; начало и конец ставятся там, где сейчас медиа, или сдвигаются клавишами; реплики делятся, объединяются, добавляются и удаляются, у окна своя отмена. Субтитры видны на видео так, как их увидит ученик; «Сохранить файл…» сохраняет их в WebVTT или SubRip.

**Маркеры открывают пузырь у точки**

- Точка «Маркеров на картинке» — на слайде и в лонгриде — открывает пояснение в пузыре рядом с собой, а не в панели или окне поверх затемнённой страницы. Стрелки переходят от точки к точке, Escape закрывает. Курсы, сделанные раньше, тоже получают пузырь.
- На телефоне в вертикальном положении пузырь слайда встаёт в пустую полосу под слайдом, с линией к точке, — весь слайд остаётся на виду.

**ИИ-ассистент проверяет свою работу**

- Код, который пишет ассистент, — упражнение на коде, HTML-объект, блок кода лонгрида — пробуется до вставки, а упражнение проигрывается движком самого курса: «верно» и «неверно» должны показывать ответ курса. Что не прошло, один раз уходит ассистенту на исправление; что не прошло и тогда, не вставляется, и чат говорит почему.
- Чат говорит, что меняет ответ: слайды и уроки, слова до и после, оформление, триггеры, переменные, тему. Ответ больше чем из восьми изменений ждёт «Применить» или «Отклонить»; меньший вставляется сразу, под ним — «Что изменилось».

**Импорт из PowerPoint**

- Презентация с повреждённым или очень большим видео, с картинками по ссылке на внешние файлы теперь переносится: слайды, текст и картинки, без видео и звука. Уведомление говорит, что не перенесено и почему.

**Для ИТ-отдела**

- Политику модели компании можно задать групповой политикой в реестре Windows (`HKLM` или `HKCU\SOFTWARE\Policies\Slidekit\AI`), те же поля, что в файле политики; реестр важнее файла.
- Claude Code и Codex, поставленные через npm на Windows, находятся — папка npm, nvm-windows, Volta, scoop, — даже если их поставили после входа в систему.
- Ключи модели компании и служб озвучки хранятся новыми методами хранилища ключей системы; сохранённые раньше ключи переходят сами.

**Названия:** «Листалка с картинками» теперь «Карусель», «На картинке» — «Маркеры на картинке»; в лонгриде «Утверждение» — «Тезис», как на слайдах, а заметка «Осторожно» — «Внимание» (так её называет и экранный диктор).

**Исправлено:** рамка фокуса в пузыре маркера видна в Firefox.

**Внутри:** Electron 45.3.4 (Chromium 156.0.8078.100), как в beta 2.

**Важно:** формат курса остаётся v95: курсы открываются и в 0.7.0-beta.2, и в 0.7.0-beta.3; курсы из прежних бет открываются и обновляются.

**Требования:** macOS 13 и новее (Apple silicon или Intel), Windows 10/11 x64, окно не уже 1280 px. **Руководство:** «Справка → Руководство» в программе, на русском и английском.

**Известные ограничения**

- Автообновления пока нет: новые версии ставятся вручную.
- Установщики не подписаны.
- Ещё не проверено на настоящих машинах — расскажите, как пройдёт: ключи в Связке ключей macOS и в Windows с новыми методами хранилища; Claude Code и Codex, поставленные через npm, nvm-windows, Volta или scoop; политика из реестра Windows. Собственные запускатели Volta пока могут не находиться.
- На Windows запись симуляций, ролик MP4, поиск личных данных и голоса системы ещё не проверены на настоящих машинах.
- В просмотре внутри редактора анимация Rive показывает первый кадр — проверяйте её через «Открыть в браузере». Файлы с бесплатного тарифа Rive показывают заставку Rive.
- Голосовым службам, кроме системной, нужен свой ключ или модель компании.

**Обратная связь:** nvadeveloper@gmail.com или «Справка → Сообщить о проблеме или предложить идею…» в программе.
