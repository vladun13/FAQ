# 🤔 FAQ

---

> Заметка: FAQ — это аббревиатура от Frequently Asked Questions (часто задаваемые вопросы).

---

### Вопрос: как установить Node.js?
###### Ответ: [скачать с официального сайта](https://nodejs.org/en/) и установить последнюю версию Node.js.

### Вопрос: как установить или обновить Git?
###### Ответ: [скачать с официального сайта](https://git-scm.com/download/) и установить последнюю версию Git.

### Вопрос: как обновить Node.js?
###### Ответ: возможно два варианта.
> `Первый`: если вы установили Node.js установщиком с сайта, то обновить тоже нужно с помощью [установщика последней версии](https://nodejs.org/en/).

> `Второй`: если вы установили Node.js [через `nvm`](https://github.com/creationix/nvm), то обновить тоже нужно с помощью команды `nvm install --lts --latest-npm`.

### Вопрос: в чём разница между [npm](https://www.npmjs.com/) и [yarn](https://yarnpkg.com/en/docs)?
###### Ответ: это два разных менеджера npm-пакетов. Можно почитать об их отличиях [здесь](https://ua-blog.com/npm-vs-yarn-%D0%BA%D0%B0%D0%BA%D0%BE%D0%B9-%D0%BC%D0%B5%D0%BD%D0%B5%D0%B4%D0%B6%D0%B5%D1%80-%D0%BF%D0%B0%D0%BA%D0%B5%D1%82%D0%BE%D0%B2-%D1%81%D1%82%D0%BE%D0%B8%D1%82-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB/) и [здесь](https://blog.risingstack.com/yarn-vs-npm-node-js-package-managers/).

### Вопрос: что лучше — [npm](https://www.npmjs.com/) или [yarn](https://yarnpkg.com/en/docs)?
###### Ответ: на этот, как и на многие другие вопросы типа «а что лучше...?», увы, ответа-серебрянной пули нет.
> У каждого пакета есть свои достоинства и недостатки. Мы используем [yarn](https://yarnpkg.com/en/docs), так как по нашему мнению он обладает более удобным и красивым интерфейсом.

### Вопрос: почему весь мой код подсвечивает редактор?
###### Ответ: возможно два варианта.
> `Первый`: ваш редактор расценивает код как неправильный. Это может произойти, когда вы пишете разметку JSX React без поддержки вашим редактором такого синтаксиса. Чтобы включить поддержку — нужно скачать соответствующий плагин для редактора. [Вот пример](https://atom.io/packages/language-babel) такого плагина для редактора Atom.

> `Второй`: ваш код подсвечивает линтер, указывая на стилистические ошибки.

### Вопрос: что такое линтер?
###### Ответ: линтер — это статический анализатор кода.
> Он сообщает разработчику о стилистических и функциональных ошибках в программном коде. Мы используем [ESLint для JavaScript](https://eslint.org/), и [stylelint для CSS](https://stylelint.io/) . Детально о том, как работает линтер на примере ESLint можно [узнать здесь](https://www.youtube.com/watch?v=hppJw2REb8g).

### Вопрос: как остановить запущенный командой npm run start (или yarn start) проект?
###### Ответ: В терминале нажми сочетание клавиш `CTRL` + `C`.
