Slidekit 0.7 beta 2 — a desktop editor for interactive e-learning courses: slide courses and longreads. What's new since 0.7.0-beta.1.

**Download:** `.dmg` for macOS (Apple silicon or Intel), `.exe` for Windows 10/11. The installers are not signed yet — see «Installing the beta» in the README for the one-time steps.

**Questions: «Next» waits for the answer**

- A question has the switch «An answer is required to go on»: while it is on, «Next» — the slide's, the player's, a menu's, a trigger's — waits until the learner answers. Any answer, the last try or the time running out lets the learner go on. New questions have it on; you can turn it off for a question that may be skipped. Questions in courses made before keep holding «Next», as they did.
- The «Correct» and «Incorrect» windows of new questions say «Continue» — the window closes and the course goes on. «Try again» still says «Answer again».

**The AI assistant's chat**

- **Back to a message:** each of your messages offers «Take the course back to this moment» — the course becomes as it was just before that message, in one undo step; «Undo» brings everything back.
- **A queue:** while the assistant works, keep writing — Enter or «Queue» puts the message in a queue under the chat, where it can be rewritten or removed; queued messages go one by one.
- **Hide the AI:** a setting in «Settings» hides the assistant, the AI windows and buttons in both editors — for a team or a course without AI.

**The company's model**

- A busy server is asked again by itself (up to four times, waiting as the server asks); «Stop» ends the wait.
- Headers of your own and an API version for your gateway; a secret header is kept in the system's key store, like the key.
- Models that speak the Anthropic Messages API, besides OpenAI-compatible ones.
- The model's context window: long conversations are shortened from the oldest messages, and the chat says so.
- A PDF goes to the model as a document when it speaks the Anthropic API and sees pictures.

**Objects touching**

- An outline's stroke touches too, and an object in a scroll panel touches where the learner scrolled it, not where it was placed.

**LMS**

- **SCORM 2004:** the course's own «Exit» — a trigger's «Exit the course», a longread's button that ends it — now asks the LMS to leave the course: an unfinished course goes on from where the learner left it next time, a finished one ends its attempt.
- **xAPI:** a launch whose registration is not a UUID no longer loses every record — the course reports without it.

**Longreads**

- The «Course theme» window starts with colours, fonts and rounding, its sections evenly spaced.
- The longread's top bar fits any window width: its buttons keep their signs, then move into «More».

**Fixed**

- Icons and formulas in the words — a list's and a card's icons, an icon or a formula in a line — now show when a course is opened from a file («Open in browser», a web package) or in an LMS on another address; before, the browser showed empty squares.
- A longread made with «Course from a document» opens with a cover photo, not an empty cover.

**Under the hood:** Electron 45.3.4 (Chromium 156.0.8078.100).

**Note:** the course format is now v95. Courses from earlier betas open in 0.7.0-beta.2 and are brought up to date as they open; courses saved in 0.7.0-beta.2 do not open in 0.7.0-beta.1 or earlier.

**Requirements:** macOS 13 or later (Apple silicon or Intel), Windows 10/11 x64, a window at least 1280 px wide. **Guide:** Help → Guide in the app, in English and Russian.

**Known limitations**

- No automatic updates yet: install new versions by hand.
- The installers are not code-signed.
- A Rive animation shows its first frame in the editor's preview — check it with «Open in browser». Files from Rive's free plan show Rive's splash screen.
- On Windows, recording simulations, the MP4 video, finding personal data and the system's voices have not been tried on real machines yet — tell us how it goes.
- Voice services other than the system's need your own key or your company's model.

**Feedback:** nvadeveloper@gmail.com or Help → Report a Problem or Suggest an Idea… in the app.

---

Slidekit 0.7 beta 2 — настольный редактор интерактивных курсов: слайдовых и лонгридов. Что нового с 0.7.0-beta.1.

**Скачать:** `.dmg` для macOS (Apple silicon или Intel), `.exe` для Windows 10/11. Установщики пока не подписаны — однократные шаги описаны в README, раздел «Installing the beta».

**Вопросы: «Далее» ждёт ответа**

- У вопроса есть переключатель «Ответ обязателен для перехода»: пока он включён, «Далее» — слайда, плеера, меню, триггера — ждёт, пока ученик ответит. Любой ответ, последняя попытка или конец времени пускают дальше. У новых вопросов он включён; у вопроса, который можно пропустить, его можно выключить. Вопросы в курсах, сделанных раньше, держат «Далее», как и держали.
- Окна «Верно» и «Неверно» у новых вопросов говорят «Продолжить» — окно закрывается, и курс идёт дальше. «Попробуйте ещё раз» по-прежнему говорит «Ответить ещё раз».

**Чат ИИ-ассистента**

- **Возврат к сообщению:** у каждого вашего сообщения — «Вернуть курс к этому моменту»: курс становится таким, каким был перед этим сообщением, одним шагом отмены; «Отменить» возвращает всё.
- **Очередь:** пока ассистент работает, пишите дальше — Enter или «В очередь» ставит сообщение в очередь под чатом, там его можно переписать или убрать; сообщения из очереди уходят по одному.
- **Скрыть ИИ:** настройка в «Настройках» прячет ассистента, окна и кнопки ИИ в обоих редакторах — для команды или курса без ИИ.

**Модель компании**

- Занятый сервер спрашивается снова сам (до четырёх раз, с паузой, которую просит сервер); «Остановить» прерывает ожидание.
- Свои заголовки и версия API для шлюза компании; секретный заголовок хранится в хранилище ключей системы, как ключ.
- Модели с API Anthropic Messages, а не только совместимые с OpenAI.
- Окно контекста модели: длинный разговор сокращается с самых ранних сообщений, и чат об этом говорит.
- PDF уходит модели документом, если она говорит на API Anthropic и видит картинки.

**Касание объектов**

- Касается и обводка контура, а объект в панели прокрутки касается там, куда ученик её прокрутил, а не там, где он поставлен.

**LMS**

- **SCORM 2004:** собственный «Выход» курса — триггер «Выйти из курса», кнопка лонгрида, которая его завершает, — теперь просит LMS выйти из курса: незаконченный курс в следующий раз продолжится с того же места, законченный завершает попытку.
- **xAPI:** запуск, у которого регистрация не в виде UUID, больше не теряет все записи — курс отчитывается без неё.

**Лонгриды**

- Окно «Тема курса» начинается с цветов, шрифтов и скругления, разделы — с ровными отступами.
- Верхняя панель лонгрида помещается в окно любой ширины: кнопки сначала остаются значками, потом уходят в «Ещё».

**Исправлено**

- Иконки и формулы в тексте — иконки списков и карточек, иконка или формула в строке — теперь видны, когда курс открыт из файла («Открыть в браузере», веб-пакет) или в LMS на другом адресе; раньше браузер показывал пустые квадраты.
- Лонгрид, созданный через «Курс из документа», открывается с фото на обложке, а не с пустой обложкой.

**Внутри:** Electron 45.3.4 (Chromium 156.0.8078.100).

**Важно:** формат курса теперь v95. Курсы из прежних бет открываются в 0.7.0-beta.2 и обновляются при открытии; курсы, сохранённые в 0.7.0-beta.2, в 0.7.0-beta.1 и раньше не открываются.

**Требования:** macOS 13 и новее (Apple silicon или Intel), Windows 10/11 x64, окно не уже 1280 px. **Руководство:** «Справка → Руководство» в программе, на русском и английском.

**Известные ограничения**

- Автообновления пока нет: новые версии ставятся вручную.
- Установщики не подписаны.
- В просмотре внутри редактора анимация Rive показывает первый кадр — проверяйте её через «Открыть в браузере». Файлы с бесплатного тарифа Rive показывают заставку Rive.
- На Windows запись симуляций, ролик MP4, поиск личных данных и голоса системы ещё не проверены на настоящих машинах — расскажите, как пройдёт.
- Голосовым службам, кроме системной, нужен свой ключ или модель компании.

**Обратная связь:** nvadeveloper@gmail.com или «Справка → Сообщить о проблеме или предложить идею…» в программе.
