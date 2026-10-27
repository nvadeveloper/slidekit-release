Slidekit 0.5 beta — a desktop editor for interactive slide-based e-learning courses. What's new since 0.4.0-beta.1.

**Download:** `.dmg` for macOS (Apple silicon or Intel), `.exe` for Windows 10/11. The installers are not signed yet — see «Installing the beta» in the README for the one-time steps.

**New: voice-over**

- **Speak text:** Media → «Speak text…» voices the slide's notes or any text: the system's voices offline, your company's model, Yandex SpeechKit or ElevenLabs with your own key (keys stay in the system's keychain, never in the course). Listen before inserting; captions come from the same text; the sound is marked «AI voice».
- **Voice again:** a synthesized sound speaks its corrected or translated text in the same voice.
- **Captions by speech recognition:** for a sound or a video, through your company's model.

**New: dialogue trainers**

- **Branching conversations:** Blocks → Scenarios → «Dialogue trainer…» — a map of lines and endings, characters with faces, scores by criteria (empathy, accuracy…), a debrief of the learner's answers at the end, every answer in the LMS report. Checks find lines nobody reaches and dead ends.
- **Write with AI** from a short brief; **voice the lines** in each character's voice.

**New exercises**

- **Gaps in a text:** typed, chosen from a list or placed from a word bank, written as «Paris is the capital of [France]».
- **Matrix:** statements on a scale — a survey or a check.
- **Questions in a video:** a trigger fires when a video reaches a moment — pause it and show a question; **chapters** let the learner jump to a part.
- **Before and after:** two pictures with a curtain the learner drags.
- The assistant writes gaps and matrices on request; gaps come in from a question table (CSV) and from GIFT «missing word».

**Software simulations, further**

- Checked typing (exact text, one of several, a number in a range), several right places and your own words for a miss, scrolling and hover steps, each step a line in the LMS report.
- «Re-record from this step…» and «Replace screenshot…»; «Find personal data» reads the screenshots on your computer and blurs e-mails, phones and numbers.
- «PDF instructions…» turns a recording into step-by-step instructions with screenshots.

**Also new:** the trigger action «Write to the LMS report» and the event «Object scrolled».

**Note:** courses saved in 0.5 use course format v34 and do not open in 0.4. Courses from 0.4 open in 0.5 as they are.

**Requirements:** macOS 13 or later (Apple silicon or Intel), Windows 10/11 x64, a window at least 1280 px wide. Recording on a Mac asks once for «Screen Recording» and «Input Monitoring». **Guide:** Help → Guide in the app, in English and Russian.

**Known limitations**

- No automatic updates yet: install new versions by hand.
- The installers are not code-signed.
- On Windows, recording simulations, finding personal data and the system's voices have not been tried on real machines yet — tell us how it goes.
- With the player's own «Back» and «Next» turned on, «Next» on a dialogue's slides goes in slide order, not by the branch; they are off by default.
- Voice services other than the system's need your own key or your company's model.

**Feedback:** nvadeveloper@gmail.com or Help → Report a Problem or Suggest an Idea… in the app.

---

Slidekit 0.5 beta — настольный редактор интерактивных слайдовых курсов. Что нового с 0.4.0-beta.1.

**Скачать:** `.dmg` для macOS (Apple silicon или Intel), `.exe` для Windows 10/11. Установщики пока не подписаны — однократные шаги описаны в README, раздел «Installing the beta».

**Новое: озвучка**

- **Озвучить текст:** «Медиа → Озвучить текст…» озвучивает заметки слайда или любой текст: голосами системы без сети, моделью вашей компании, Yandex SpeechKit или ElevenLabs по вашему ключу (ключи — в хранилище системы, не в курсе). Можно прослушать до вставки; субтитры строятся из того же текста; звук помечен «Голос ИИ».
- **Переозвучка:** синтезированный звук озвучивает исправленный или переведённый текст тем же голосом.
- **Субтитры распознаванием речи** у звука и видео — через модель компании.

**Новое: диалоговые тренажёры**

- **Разговор с ветвлением:** «Блоки → Сценарии → Диалоговый тренажёр…» — схема реплик и концовок, персонажи с выражениями, баллы по критериям (эмпатия, точность…), разбор ответов на концовке, каждый ответ — строка в отчёте LMS. Проверки находят реплики, куда никто не попадает, и тупики.
- **Создать с ИИ** по брифу; **озвучить реплики** голосом каждого персонажа.

**Новые упражнения**

- **Пропуски в тексте:** вписать, выбрать в списке или поставить из банка слов; пишутся так: «Столица Франции — [Париж]».
- **Матрица:** утверждения по шкале — опрос или проверка.
- **Вопросы в видео:** триггер срабатывает, когда видео доходит до заданной секунды — поставьте его на паузу и покажите вопрос; **главы** — переход к нужной части.
- **До и после:** две картинки и шторка, которую тянет ученик.
- Помощник пишет пропуски и матрицу по просьбе; пропуски переносятся из таблицы вопросов (CSV) и из «пропущенного слова» GIFT.

**Симуляции программ — дальше**

- Проверка ввода (точный текст, один из вариантов, число в диапазоне), несколько верных мест и своё пояснение к промаху, шаги прокрутки и наведения, каждый шаг — строка в отчёте LMS.
- «Переснять с этого шага…» и «Заменить снимок…»; «Найти личные данные» читает снимки прямо на компьютере и размывает почту, телефоны и номера.
- «Инструкция PDF…» делает из записи пошаговую инструкцию со снимками.

**Ещё новое:** действие триггера «Записать в отчёт LMS» и событие «Объект прокручивают».

**Важно:** курсы, сохранённые в 0.5, записаны в формате v34 и в 0.4 не открываются. Курсы из 0.4 открываются в 0.5 как есть.

**Требования:** macOS 13 или новее (Apple silicon или Intel), Windows 10/11 x64, окно от 1280 px в ширину. Запись на Mac один раз спрашивает «Запись экрана» и «Мониторинг ввода». **Руководство:** «Справка → Руководство» в программе, на русском и английском.

**Известные ограничения**

- Автообновления пока нет: новые версии ставятся вручную.
- Установщики не подписаны.
- На Windows запись симуляций, поиск личных данных и голоса системы на настоящих машинах ещё не проверялись — расскажите, как пройдёт.
- Если включить в плеере свои кнопки «Назад» и «Далее», «Далее» на слайдах диалога идёт по порядку слайдов, а не по ветке; по умолчанию они выключены.
- Службам озвучки, кроме голосов системы, нужен ваш ключ или модель компании.

**Обратная связь:** nvadeveloper@gmail.com или «Справка → Сообщить о проблеме или предложить идею…» в программе.
