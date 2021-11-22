# [Buefy CSS Variables](https://buefy.org)

> Buefy is a lightweight library of responsive UI components for [Vue.js](https://vuejs.org/) based on [Bulma](http://bulma.io/) framework and design.

## ⚠️ DEPRECATION WARNING ⚠️

This package has been deprecated.

Please find new and updated Bulma and Buefy styles with CSS Variables at [@bulvar/buefy](https://github.com/daniil4udo/bulvar)

## Features

* Uses CSS variables and have Bulma CSS Variables as dependency
* Keep your current Bulma theme / variables easily
* Supports both [Material Design Icons](https://materialdesignicons.com/) and [FontAwesome](http://fontawesome.io/)
* Very lightweight with none internal dependencies aside from Vue & Bulma
* About 88KB min+gzip (with Bulma included)
* Semantic code output
* Follows Bulma design and some of the [Material Design UX](https://material.io/)
* Focus on usability and performance without *over-animating* stuff

## Documentation

The documentation is in the docs directory, it serves as the demo as well.

Browse [online documentation here](https://buefy.org/).

## Quick start

You need [Vue.js](https://vuejs.org/) **version 2.6+**.

### 1 Install via npm

```bash
npm install buefy
```

### 2 Import and use Buefy

Bundle
```javascript
import Vue from 'vue';
import Buefy from 'buefy';
import 'buefy-css-variables/dist/buefy.css';

Vue.use(Buefy);

```
or Individual Components
```javascript

import Vue from 'vue'
import { Field, Input } from 'buefy'
import 'buefy-css-variables/dist/buefy.css'

Vue.use(Field)
Vue.use(Input)

```

### 3 Include Material Design Icons

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@mdi/font@5.8.55/css/materialdesignicons.min.css">
```

If you want to customize the icons or the theme, refer to the [customization section on the documentation](https://buefy.org/documentation/customization).

## Browser support

Recent versions of Firefox, Chrome, Edge, Opera and Safari. IE10+ is not supported due to the use of CSS variables.

## Contributing

Please see the [contributing guidelines](./.github/CONTRIBUTING.md)

## Versioning

Version will follow **v0.Y.Z**, where:

* **Y**: Major (breaking changes)
* **Z**: Minor or patch

## Core Team

<table>
  <tr>
    <td align="center"><a href="https://twitter.com/walter_tommasi"><img src="https://avatars0.githubusercontent.com/u/8029488?v=4" width="80px;" alt=""/><br /><sub><b>Walter Tommasi</b></sub></a><br /></td>
  </tr>
</table>

Special thanks to <a href="http://twitter.com/rafaelpimpa">Rafael Beraldo</a>, the original author.

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## License <a href="https://github.com/buefy/buefy/blob/master/LICENSE"><img src="https://img.shields.io/npm/l/buefy.svg?logo=github" /></a>

Code released under [MIT](https://github.com/buefy/buefy/blob/master/LICENSE) license.
