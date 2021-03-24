# getCodingKnowledge Extension Pack

getCodingKnowledge Extension Pack est une collection des extensions que j'utilise sur [mes différentes vidéos](https://www.youtube.com/c/getcodingknowledge).

## Extensions inclus

En installant mon pack, ces extensions seront installées:

- [📦 .gitignore Generator](https://marketplace.visualstudio.com/items?itemName=piotrpalarz.vscode-gitignore-generator)
  - Generate .gitignore file using gitignore.io API
- [📦 Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  - Human-friendly comments in your code
- [📦 Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
	- A customizable extension for colorizing matching brackets
- [📦 Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
  - Improve highlighting of errors, warnings and other language diagnostics
- [📦 Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
  - View a Git Graph of your repository, and easily perform Git actions from the graph.
- [📦 Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  - Display import/require package size in the editor
- [📦 Moxer Icons](https://marketplace.visualstudio.com/items?itemName=Equinusocio.moxer-icons)
  - Moxer Icons, the epic icons companion for Moxer Theme
- [📦 getCodingKnowledge Theme](https://marketplace.visualstudio.com/items?itemName=noxaled.gck-theme)
  - Theme I'm using in my latest videos
- [📦 Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
  - AI-assisted development

## Themes

J'utilise trois thèmes, un pour mes vidéos, un autre perso et un ancien de temps en temps. Voici les extensions:

- getCodingKnowledge Theme (thème des nouvelles vidéos)

### Ancien thèmes perso

- Rainglow (new theme) & Moxer (icons)
- Dark+ (le thème des nouvelles vidéos (thème par défaut de VSCode))
- Gruvbox Theme (thème de mes anciennes vidéos)
  - Nom du thème: Gruvbox Dark Medium
- Dobri Next (Ancien Themes and Icons)
- Moxer Theme (ancien thème perso)
  - Nom du thème: Moxer
- Ayu (ancien thème perso)
  - Nom du thème: Ayu Dark Bordered

La police que j'utilise dans les vidéos -> Consolas
La police que j'utilise personellement -> CascadaCode

## Settings

Vous pouvez aussi copier les paramètres que j'utilise en ouvrant `Preferences: Open Settings (JSON)` via `CTRL + SHIFT + P` puis en collant le code ci-dessous:

```json
{
	"editor.minimap.enabled": false,
	"editor.tabSize": 2,
	"editor.wordWrap": "on",
	"workbench.activityBar.visible": false,
	"workbench.statusBar.visible": true,
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
		"editor.defaultFormatter": "esbenp.prettier-vscode"
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
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"editor.fontFamily": "Cascadia Code",
	"editor.fontLigatures": false,
	"editor.fontSize": 14,
	"workbench.tree.indent": 22,
	"kite.showWelcomeNotificationOnStartup": false,
	"window.zoomLevel": 2,
	"workbench.iconTheme": "moxer-icons",
	"workbench.colorTheme": "Rainbow Contrast (rainglow)"
}

```

## License

[MIT](https://github.com/noxaled/gckn-pack/blob/master/LICENSE.txt)