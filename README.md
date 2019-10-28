# Configurações do Visual Studio Code

Este é um repositório com todas as **configurações** do meu vscode e outros **plugins** e **ferramentas** que uso para desenvolvimento.

Grande parte dessas configurações foram baseadas no padrão utilizado pela **Rocketseat**, especificamente pelo instrutor [Diego Fernandes](https://github.com/diego3g).

<hr />

## 🔗 Extensões

Essas são as extensões/plugins que uso para configurar o editor **Visual Studio Code**:

- GitLeans
- EditorConfig for VS Code
- Rocketseat ReactJS
- Rocketseat React Native
- ESLint
- Prettier
- Dracula Official
- Color Highlight
- Bracket Pair Colorizer
- material-icon-theme
- vscode-styled-components

<hr />

## ⚙️ Settings.json

Segue abaixo as **configurações completas** em formato JSON do vscode. Para utiliza-las basta na aba preferences no vscode, abrir e alterar o arquivo **settings.json**.

```javascript
{
  // Styles settings
  "workbench.colorTheme": "Dracula",
  "workbench.iconTheme": "material-icon-theme",
  "editor.fontFamily": "Fira Code",
  "editor.fontSize": 18,
  "editor.lineHeight": 24,
  "editor.fontLigatures": true,
  "editor.letterSpacing": 0,
  "editor.tabSize": 2,
  "editor.renderLineHighlight": "gutter",
  "window.zoomLevel": 0,
  "breadcrumbs.enabled": true,
  "terminal.integrated.fontSize": 14,
  "editor.rulers": [
    80,
    120
  ],

  // IDE settings
  "editor.formatOnSave": true,
  "editor.parameterHints.enabled": false,
  "workbench.startupEditor": "newUntitledFile",
  "javascript.updateImportsOnFileMove.enabled": "never",

  // Pattern code settings
  "prettier.singleQuote": true,
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  }
}
```

<hr />

## 🔤 Fonte

Para instalar a fonte basta abrir a pasta [~/fonts/FiraCode/](./fonts/FiraCode/) baixar a versão da fonte desejada e clicar em instalar, independente do sistema operacional. Após isso basta utilizar a fonte, alterando as configurações do vscode, como listado acima.

<hr />

## 🛠️ Ferramentas utilizadas

Essas são algumas ferramentas **essenciais** que uso para desenvolvimento.

- [insomnia](https://insomnia.rest/download/) / [postman](https://www.getpostman.com/downloads/)
- [vscode](https://code.visualstudio.com/download)
- [yarn](https://yarnpkg.com/lang/en/) / [npm](https://nodejs.org/en/download/)
- [git](https://git-scm.com/downloads)
- [devdocs app](https://devdocs.egoist.moe/)
- [extensão chrome react](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en-US)
- [extensão chrome dracula](https://chrome.google.com/webstore/search/dracula%20devtools?hl=en-US)

<hr />

## 🖥️ Terminal

### Font

Click with the right bottom in the terminal and choose **Fira code** font as default.

Download [dracula theme](https://draculatheme.com/terminal/)

### Installing and setting [Oh My Zsh](https://ohmyz.sh/)

Adding styles with [Spaceship](https://github.com/denysdovhan/spaceship-prompt)

Open the **zshrc** file:

```shell
  # code ~/.zshrc
```

Change `ZSH_THEME="robbyrussell"` to `ZSH_THEME="spaceship"`

Add another configurations to zsh file:

```shell
  SPACESHIP_PROMPT_ORDER=(
    user
    dir
    host
    git
    exec_time
    line_sep
    vi_mode
    jobs
    exit_code
    char
  )

  SPACESHIP_PROMPT_ADD_NEW_LINE=false
  SPACESHIP_CHAR_SYMBOL=">"
  SPACESHIP_CHAR_SUFFIX=" "
```

To add some plugins, first install [zplugin](https://github.com/zdharma/zplugin)

In the zsh file add:

```
  zplugin light zsh-users/zsh-autosuggestions
  zplugin light zsh-users/zsh-completions
  zplugin light zdharma/fast-syntax-highlighting
```
