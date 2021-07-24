# getCodingKnowledge Extension Pack

getCodingKnowledge Extension Pack est une collection des extensions que j'utilise sur [mes différentes vidéos](https://www.youtube.com/c/getcodingknowledge).

## Extensions inclus

En installant mon pack, ces extensions seront installées:

- [📦 .gitignore Generator](https://marketplace.visualstudio.com/items?itemName=piotrpalarz.vscode-gitignore-generator)
  - Generate .gitignore file using gitignore.io API
- [📦 Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  - Human-friendly comments in your code
- [📦 Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
  - Improve highlighting of errors, warnings and other language diagnostics
- [📦 Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
  - View a Git Graph of your repository, and easily perform Git actions from the graph
- [📦 Moxer Icons](https://marketplace.visualstudio.com/items?itemName=Equinusocio.moxer-icons)
  - Moxer Icons, the epic icons companion for Moxer Theme
- [📦 Gruvbox](https://marketplace.visualstudio.com/items?itemName=wheredoesyourmindgo.gruvbox-concoctis)
  - Concoction of Gruvbox themes
- [📦 Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)
	- Automating the process of writing meaningful log messages
- [📦 TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
	- Highlight TODOs, FIXMEs, and any keywords, annotations...
- [📦 GitLive](https://marketplace.visualstudio.com/items?itemName=TeamHub.teamhub)
	- Real-time features remote development teams need to work together effectively
- [📦 Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
  - AI-assisted development

## Themes

J'utilise en général trois thèmes, un pour mes vidéos, un autre perso et un ancien de temps en temps. Cependant, ces dernières temps je n'en utilise que deux:

- Dark+ (le thème des nouvelles vidéos (thème par défaut de VSCode))
- Gruvbox Concoctis & Moxer (icons)

La police que j'utilise dans les vidéos -> Consolas
La police que j'utilise personellement -> Hack Nerd Font

### Ancien thèmes perso

- getCodingKnowledge Theme (perso) & Moxer (icons)
- Rainglow 
- Gruvbox Theme
  - Nom du thème: Gruvbox Dark Medium
- Dobri Next 
- Moxer Theme
  - Nom du thème: Moxer
- Ayu
  - Nom du thème: Ayu Dark Bordered

## Settings

Vous pouvez aussi copier les paramètres que j'utilise en ouvrant `Preferences: Open Settings (JSON)` via `CTRL + SHIFT + P` puis en collant le code ci-dessous:

```json
{
	"editor.minimap.enabled": false,
	"editor.tabSize": 2,
	"editor.wordWrap": "on",
	"files.exclude": {
			"**/.classpath": true,
			"**/.project": true,
			"**/.settings": true,
			"**/.factorypath": true
	},
	"explorer.confirmDelete": false,
	"extensions.ignoreRecommendations": true,
	"explorer.confirmDragAndDrop": false,
	"workbench.sideBar.location": "right",
	"editor.suggestSelection": "first",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"[javascript]": {
			"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"prettier.arrowParens": "avoid",
	"prettier.singleQuote": true,
	"prettier.trailingComma": "all",
	"prettier.useTabs": true,
	"git.enableSmartCommit": true,
	"git.autofetch": true,
	"prettier.endOfLine": "auto",
	"prettier.proseWrap": "never",
	"[json]": {
			"editor.defaultFormatter": "vscode.json-language-features"
	},
	"editor.fontFamily": "Cascadia Code",
	"editor.fontLigatures": false,
	"editor.fontSize": 14,
	"workbench.tree.indent": 10,
	"workbench.iconTheme": "moxer-icons",
	"workbench.colorTheme": "gruvboxConcoctis dark hard",
	"zenMode.centerLayout": false,
	"zenMode.hideLineNumbers": false,
	"explorer.compactFolders": false,
	"window.zoomLevel": 2,
	"workbench.activityBar.visible": false
}
```

## License

[MIT](https://github.com/noxaled/gckn-pack/blob/master/LICENSE.txt)