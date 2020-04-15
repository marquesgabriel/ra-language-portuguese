# Portuguese Translations for react-admin

Portuguese translations for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST services.

## Installation

```sh
yarn add @henriko/ra-language-portuguese

#or

npm install @henriko/ra-language-portuguese
```

## Usage

```js
import portugueseMessages from "@henriko/ra-language-portuguese";
import polyglotI18nProvider from "ra-i18n-polyglot";

const messages = {
  pt: portugueseMessages,
};

const i18nProvider = polyglotI18nProvider((locale) => messages[locale], "pt");

<Admin i18nProvider={i18nProvider}>...</Admin>;
```

This project was forked and adapted from original's [ra-language-portuguese](https://github.com/marquesgabriel/ra-language-portuguese) project.

## License

This translation is licensed under the [MIT Licence](LICENSE)
