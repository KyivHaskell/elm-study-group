# Група з вивчення мови Елм

## Принципи

Ми працюватимемо за книгою [Elm in Action](https://www.manning.com/books/elm-in-action) авторства Річарда Фелдмана, доповненою домашніми завданнями. Передумовами для участі є ця книга, лаптоп, знання англійської (на рівні читання простої мови зі словником), та ви. Також знадобляться базові знання HTML, CSS, та JavaScript, або будь-якої іншої мови програмування. Жодного попереднього досвіду з Елмом не потрібно. Досвід з функційним програмуванням теж не потрібен, але на цьому курсі обширних знань ви не отримаєте. Одна з цілей цього курсу – підготувати вас до поглибленого вивчення функційного програмування мовою Haskell, рекомендуємо слідкувати за [курсом з Haskell](https://github.com/KyivHaskell/haskell-study-group), що почнеться по завершенні цієї групи.

Для підготовки до вашого першого візиту, будь ласка, зробіть наступне:

- **Доєднайтесь до [Telegram-каналу #KyivElm](https://t.me/KyivElm).** Всі анонси, що стосуються цієї групи з вивчення будуть надіслані через [Meetup.Vodka](https://meetup.vodka/index.html#meetup/1) та Telegram.

- **[Придбайте](https://www.manning.com/books/elm-in-action) свою особисту копію книги**
Вам знадобиться власна копія на вашому комп’ютері задля того, щоби працювати із PDF-контентом та редактором, відкритими поруч. Цю книжку було незалежно досліджено, написано та видано Елм-розробником, що працював в свій вільний час для підтримки навчання функційному програмуванню мовою Елм. Будучи членом стійкої та підтримувальної спільноти, ми знаємо, що ви занадто віддані духу благої дії "позичити" чиюсь копію. Будь ласка, поважайте роботу автора та придбайте книгу.

- **Встановіть [Elm](https://guide.elm-lang.org/install.html)** та налаштуйте редактор.

- **Налаштуйте проектне середовище для свого практикування в кодингу, також ознайомтесь із GHC та GHCi.**
Не потрібно робити набагато більше, ніж створити директорію для вашого коду та впевнитись, що ви вмієте запускати компілятор Elm на ваших першокодах, та `elm repl`, коли вам потрібен REPL. Впевніться, що можете запустити проект https://github.com/evancz/elm-architecture-tutorial.git, який вказано на [сторінці з інструкціями по інсталяції](https://guide.elm-lang.org/install.html).

### Очікування

Очікується, що учасники групи з вивчення зможуть встановити та дотримуватись принципу самовідповідальності. Це тягне за собою зміцнення завдяки нормам підтримувального одне одного та ретельно працівного середовища. Щотижня ви маєте виконати наступні задачі:

- прочитати весь матеріал
- набрати весь код
- спробувати виконати всі завдання
- зустрітись із партнером/партнеркою із вивчення задля обговорення вашої роботи
- відвідати групову зустріч

Ці очікування було встановлено не для того, аби зробити ваше життя жалюгідним, але щоби підготувати базу вашого успіху. Якщо ви дійсно хочете вивчити Елм, ключ, як завжди, лежить в постійності та послідовності. Оскільки в цій групі ми вивчатимемо Елм разом, неодмінною є ваша самостійна праця над кожним розділом перед зустріччю, щоби ви прийшли на неї підготовленими, знаючи наперед, де саме ви потребуєте допомоги та що ви розумієте достатньо добре, аби допомогти іншим. Якщо ви застрягли із проблемою — продовжуйте рухатись, але не пропускайте вправи повністю.

#### Ще раз наголошуємо: _не пропускайте вправи!_

Якщо ви зовсім новачок у програмуванні або за якоїсь причини маєте проблеми із встановленням Елм на вашому комп’ютері, не переживайте! Приходьте в групу з вивчення, ми вам допоможемо розібратись.

### Норми поведінки

Беручи участь в цій групі з вивчення, ви погоджуєтесь із наступними нормами:

Ви придбаєте свою власну копію книги Elm in Action. Будь-кого запідозреного/запідозрену у використанні нелегальної копії буде усунено з групи негайно.

Щотижня, до групової зустрічі, ви завершите читання та намагатиметесь виконати вправи із максимальними зусиллями, доступними вам. Якщо ви не докладете істотних зусиль для виконання роботи, незалежно від причин, вас не буде допущено до групового обговорення того тижня. Учасники, що не змогли завершити свої завдання двічі поспіль або тричі в сумі, можуть бути змушені покинути групу. Якщо ви маєте проблеми із виконанням завдань, ви повинні попросити допомоги на зустрічах, від вашого партнера/партнерки з навчання, або онлайн.

Ви докладете всіх зусиль, аби взяти участь у щотижневій зустрічі. Кількість місць обмежена, тому якщо ви не впевнені в можливості регулярно долучатись, не реєструйтесь. Учасники, що постійно пропускають мітинги, або відмічаються як RSVP, не з’явившись, будуть змушені покинути групу. Якщо ви не можете попасти на мітинг, приберіть відмітку участі (RSVP) щонайшвидше.

На додаток до зазначеного, від всіх учасників групи з вивчення очікується докладання найбільших зусиль із дотримання людської поведінки. Учасники, чиї дії відходять занадто далеко або занадто часто від розумних кордонів поваги, доброзичливості, та колегіальності можуть бути усунені з групи на розсуд організаторів.

На сайті [Recurse Center](https://www.recurse.com) є корисний список [соціальних правил](https://www.recurse.com/manual#sub-sec-social-rules), із яким ми рекомендуємо ознайомлення перед відвідуванням наших зустрічей.

### Формат

Ми працюватимемо крізь розділи 1-7 книги Elm in Action протягом 7 тижнів, зустрічаючись приблизно на дві години щотижня. Ми можемо розширити список зустрічей для покриття поглиблених тем, якщо матимемо достатньо ентузіазму та доступність організаторів.

Тим не менш, **це не курси**, тому не очікуйте формату лекцій. Навзамін, ви матимете можливість переглянути свою роботу та обговорити концепції та вправи, із якими ви мали проблеми, коли працювали з книгою власноруч.

Ви вільні вибирати зручний вам режим роботи з книгою, плануючи роботу як завгодно близько до щотижневих зустрічей, аби ви тільки могли підтримувати власний ритм. Тому слід зазначити, що якщо життєві події стануть перешкодою, так тому і бути, але намагайтесь якомога швидше наздогнати пропущене, та не пропускайте жодних матеріалів, бо кожен наступний розділ ґрунтується на попередніх. Ми завжди можемо обговорити вправи на Telegram-каналі, але просимо втриматись від публікації ваших рішень (в тому числі на GitHub).

### Реєстрація

Всі зустрічі буде оголошено на Meetup.Vodka та Telegram. Ви маєте відмітитись як учасник (RSVP) окремо на кожну зустріч, оскільки кількість місць обмежена. Якщо ви не можете відвідати зустріч через нестачу місць, будь ласка, працюйте самостійно та приходьте на наступну зустріч. Не відмічайтесь (RSVP), якщо не можете прийти. Подібні вчинки будуть приводити до вилучення можливості відвідувати послідущі зустрічі.

### Слайди та інші ресурси

Дивіться суб-теку [resources](resources) в цьому репозиторії для презентаційних слайдів, бонусних вправ, або інших матеріалів, використаних під час зустрічей групи. Якщо ви маєте щось, що б ви хотіли додати, будь ласка, зробіть pull request.

### Розклад

**Week 1. Welcome to Elm**

- Chapter 1
- [Homework](./resources/homework-01)

**Week 2. Your First Elm Application**

- Chapter 2
- [Homework](./resources/homework-02)

**Week 3. Compiler and Assistant**

- Chapter 3
- [Homework](./resources/homework-03)

**Week 4. Talking to Servers**

- Chapter 4

**Week 5. Talking to JavaScript**

- Chapter 5

**Week 6. Testing**

- Chapter 6

**Week 7. Data Modeling**

- Chapter 7

Дні зустрічей, час, та місце проведення може змінюватись в залежності від доступності місця.

Для деталей щодо конкретної зустрічі, дивіться [сторінку на Meetup.Vodka](https://meetup.vodka/index.html#meetup/1).
