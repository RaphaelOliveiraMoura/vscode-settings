# Configurações do Visual Studio Code

Este é um repositório com todas as **configurações** do meu vscode e outros **plugins** e **ferramentas** que uso para desenvolvimento.

Grande parte dessas configurações foram baseadas no padrão utilizado pela **Rocketseat**, especificamente pelo instrutor [Diego Fernandes](https://github.com/diego3g).

## 🔗 Extensões

Essas são as extensões/plugins que uso para configurar o editor **Visual Studio Code**:

- Bracket Pair Colorizer
- Dracula Official
- Color Highlight
- GitLeans
- Prettier
- vscode-styled-components
- vscode-icons
- Rocketseat ReactJS
- Rocketseat React Native

## ⚙️ Settings.json

Segue abaixo as **configurações completas** em formato JSON do vscode. Para utiliza-las basta na aba preferences no vscode, abrir e alterar o arquivo **settings.json**.

```javascript
{
  // Styles settings
  "workbench.colorTheme": "Dracula",
  "workbench.iconTheme": "vscode-icons",
  "editor.fontFamily": "Fira Code",
  "editor.fontSize": 18,
  "editor.lineHeight": 24,
  "editor.fontLigatures": true,
  "editor.letterSpacing": 0,
  "editor.tabSize": 2,

  // IDE settings
  "editor.formatOnSave": true,
  "workbench.startupEditor": "newUntitledFile",

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

## 🔤 Fonte

Para instalar a fonte basta abrir a pasta [~/fonts/FiraCode/]() baixar a versão da fonte desejada e clicar em instalar, independente do sistema operacional. Após isso basta utilizar a fonte, alterando as configurações do vscode, como listado acima.

## 🛠️ Ferramentas utilizadas

Essas são as ferramentas **essenciais** para desenvolvimento.

- insomnia / postman
- vscode
- yarn / npm
- git

## 🖥️ Terminal
