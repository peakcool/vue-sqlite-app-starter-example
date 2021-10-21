<p align="center"><br><img src="https://avatars3.githubusercontent.com/u/16580653?v=4" width="128" height="128" /></p>

<h3 align="center">Ionic/Vue SQLite App Starter</h3>
<p align="center"><strong><code>vue-sqlite-app-starter</code></strong></p>
<p align="center">Ionic/Vue application demonstrating the use of the</p>
<p align="center"><strong><code>@capacitor-community/sqlite plugin<code></strong></p>
<p align="center" style="font-size:50px;color:red"><strong>CAPACITOR 3 </strong></p><br>
<br>
<p align="center">
  <img src="https://img.shields.io/maintenance/yes/2021?style=flat-square" />
  <a href="https://github.com/jepiqueau/vue-sqlite-app-starter"><img src="https://img.shields.io/github/license/jepiqueau/vue-sqlite-app-starter?style=flat-square" /></a>
  <a href="https://github.com/jepiqueau/vue-sqlite-app-starter"><img src="https://img.shields.io/github/package-json/v/jepiqueau/vue-sqlite-app-starter/main?style=flat-square" /></a>
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<a href="#contributors-"><img src="https://img.shields.io/badge/all%20contributors-2-orange?style=flat-square" /></a>
<!-- ALL-CONTRIBUTORS-BADGE:END -->
</p>


## Maintainers

| Maintainer        | GitHub                                    | Social |
| ----------------- | ----------------------------------------- | ------ |
| Quéau Jean Pierre | [jepiqueau](https://github.com/jepiqueau) |        |


## 🚧 To be Updated 🚧

The components `EncryptionTest.vue` and `UpgradeVersionTest.vue`have still to be created

## Installation 

To start clone the project

```bash
git clone https://github.com/jepiqueau/vue-sqlite-app-starter.git
cd ./vue-sqlite-app-starter
git remote remove origin
npm install
```

To install the latest release of the ```@capacitor-community/sqlite``` plugin

```bash
npm run update
npm run build 
npx cap sync
npx cap sync @capacitor-community/electron
npm run build
npx cap copy
npx cap copy web
npx cap copy @capacitor-community/electron
```

## Running the app

The assets databases should be in the `public/assets/databases`folder

### BROWSER

The `sql-wasm.wasm` file should be copied from `node_modules/sql.js/dist`folder to `public/assets`folder

```
npx run serve
```

### IOS

```
npx cap open ios
```

### ANDROID

```
npx cap open android
```

### ELECTRON

```
npx cap open @capacitor-community/electron
```

## Accessing the tests 🚧

Go to the Tab2 of the application


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/jepiqueau"><img src="https://avatars3.githubusercontent.com/u/16580653?v=4" width="100px;" alt=""/><br /><sub><b>Jean Pierre Quéau</b></sub></a><br /><a href="https://github.com/jepiqueau/vue-sqlite-app-starter/commits?author=jepiqueau" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/codeluggage"><img src="https://avatars.githubusercontent.com/u/1154150?v=4" width="100px;" alt=""/><br /><sub><b>Matias Forbord</b></sub></a><br /><a href="https://github.com/jepiqueau/vue-sqlite-app-starter/commits?author=jepiqueau" title="Code">💻</a></td>
    
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

