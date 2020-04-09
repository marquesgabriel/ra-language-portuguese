# Portuguese Translations for Admin-on-rest

Portuguese translations for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST services.

## Installation

```sh
yarn add ra-language-portuguese
```

## Usage

```js
import portugueseMessages from 'ra-language-portuguese'
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'pt': portugueseMessages,
};

const i18nProvider = polyglotI18nProvider((locale) => messages[locale], 'pt');

<Admin i18nProvider={i18nProvider}>
  ...
</Admin>
```

This project was forked and adapted from original's [aor-language-portugues](https://github.com/movibe/aor-language-portugues) project
## License
This translation is licensed under the [MIT Licence](LICENSE), and sponsored by [BlackBox Vision](https://github.com/BlackBoxVision).
