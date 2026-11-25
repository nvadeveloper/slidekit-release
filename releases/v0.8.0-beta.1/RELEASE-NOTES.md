Slidekit 0.8 beta 1 — a desktop editor for interactive e-learning courses: slide courses and longreads. What's new since 0.7.0-beta.4.

**Download:** `.dmg` for macOS (Apple silicon or Intel), `.exe` for Windows 10/11. The installers are not signed yet — see «Installing the beta» in the README for the one-time steps.

**Slides**

- A shape's, a button's or a picture's line can be dashed or dotted («Line: Solid · Dashes · Dots»).
- An emphasis can repeat without end («∞ Without end») — it plays while the object is on the slide.
- A change of state can spring into place («Spring»); the card flip turns as a hand turns a card.
- The length of a way in, a way out and an emphasis is dragged on the timeline in quarters of a second; the length shows beside the edge while it is dragged.
- A colour is typed as HEX or as its red, green, blue and opacity.
- A slide that holds «Next» shows in its properties what the learner is told and the course's switch for these hints.
- «Back» on the course's first slide and «Next» on its last say so when pressed.
- The results slide shows its outcome, points and buttons on a card of their own.
- A new course's title slide shows the course name typed in «Create course»; a new slide after the title page is «Title and text».

**Longreads**

- A picture beside its words at the left or the right, a third, a half or two thirds of the row.
- A gallery's pictures enlarge by a click; text and flip cards align left, centre or right; a button can wait for the blocks above it; a «Finish» button ends the course.
- Spacing «None»; one «Text colour» field; your own icon from a file; Fluent emoji.
- A sound plays in the course's own look — a round button, a line to move along, its time — not the browser's grey player.
- Slides of another course or of PowerPoint go into a lesson; blocks appear on scroll more smoothly.

**Editor**

- Five rounds of design review: the dark look, windows, folds with a drawn arrow, block panels, the start screen; «Learner clicks» instead of «User clicks»; courses from templates open without warnings.
- «Continue where you left off?» says «at slide 2 of 5».

**Under the hood:** Electron 45.5.0 (Chromium 156.0.8078.109).

**Note:** the course format is now v98. Courses from earlier betas open and are brought up to date; a course saved in 0.8.0-beta.1 does not open in 0.7.

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

Slidekit 0.8 beta 1 — настольный редактор интерактивных курсов: слайдовых и лонгридов. Что нового с 0.7.0-beta.4.

**Скачать:** `.dmg` для macOS (Apple silicon или Intel), `.exe` для Windows 10/11. Установщики пока не подписаны — один раз пройдите шаги из раздела «Установка беты» в README.

**Слайды**

- Линия фигуры, кнопки или картинки — штрихами или точками («Линия: Сплошная · Штрихи · Точки»).
- Акцент повторяется без конца («∞ Без конца»), пока объект на слайде.
- Смена состояний «Пружина»; переворот карточки — как рука переворачивает карточку.
- Длину появления, исчезновения и акцента тянут на таймлайне шагом 0,25 с; пока тянешь, длина видна у края.
- Цвет вводится в HEX или красным, зелёным, синим и прозрачностью.
- Слайд, который держит «Далее», показывает в свойствах, что увидит ученик, и общий переключатель таких подсказок.
- «Назад» на первом слайде курса и «Далее» на последнем при нажатии говорят об этом.
- Итог, баллы и кнопки слайда результатов — на своей карточке.
- На титульном слайде нового курса — название из окна «Создать курс»; новый слайд после титульного — «Заголовок и текст».

**Лонгрид**

- Картинка сбоку — слева или справа, на треть, половину или две трети строки.
- Лупа у галереи; выравнивание текста и перевёртышей; кнопка ждёт блоки выше; кнопка «Завершить» заканчивает курс.
- Отступы «Нет»; одно поле «Цвет текста»; своя иконка из файла; эмодзи Fluent.
- Звук играет в виде курса — круглая кнопка, полоса и время, а не серый плеер браузера.
- Слайды другого курса и PowerPoint — в уроке; блоки появляются при прокрутке плавнее.

**Редактор**

- Пять кругов дизайн-ревю: тёмная тема, окна, складки с нарисованной стрелкой, панели блоков, стартовый экран; «Ученик нажимает» вместо «Пользователь нажимает»; курсы из шаблонов открываются без предупреждений.
- «Продолжить с места остановки?» говорит «на слайде 2 из 5».

**Внутри:** Electron 45.5.0 (Chromium 156.0.8078.109).

**Важно:** формат курса теперь v98. Курсы из прежних бет открываются и обновляются; курс, сохранённый в 0.8.0-beta.1, не откроется в 0.7.

**Требования:** macOS 13 и новее (Apple silicon или Intel), Windows 10/11 x64, окно не уже 1280 px. **Руководство:** «Справка → Руководство» в программе, на русском и английском.

**Известные ограничения**

- Автообновления пока нет: новые версии ставятся вручную.
- Установщики не подписаны.
- Ещё не проверено на настоящих машинах — расскажите, как пройдёт: ключи в Связке ключей macOS и в Windows с новыми методами хранилища; Claude Code и Codex, поставленные через npm, nvm-windows, Volta или scoop; политика из реестра Windows. Собственные запускатели Volta пока могут не находиться.
- На Windows запись симуляций, ролик MP4, поиск личных данных и голоса системы ещё не проверены на настоящих машинах.
- В просмотре внутри редактора анимация Rive показывает первый кадр — проверяйте её через «Открыть в браузере». Файлы с бесплатного тарифа Rive показывают заставку Rive.
- Голосовым службам, кроме системной, нужен свой ключ или модель компании.

**Обратная связь:** nvadeveloper@gmail.com или «Справка → Сообщить о проблеме или предложить идею…» в программе.
