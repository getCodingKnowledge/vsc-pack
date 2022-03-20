# getCodingKnowledge Extension Pack

getCodingKnowledge Extension Pack est une collection des extensions que j'utilise sur [mes différentes vidéos](https://www.youtube.com/c/getcodingknowledge).

## Extensions inclus

En installant mon pack, ces extensions seront installées:

- [📦 .gitignore Generator](https://marketplace.visualstudio.com/items?itemName=piotrpalarz.vscode-gitignore-generator)
  - Generate .gitignore file using gitignore.io API
- [📦 AI Doc Writer](https://marketplace.visualstudio.com/items?itemName=mintlify.document)
  - AI powered documentation writer
- [📦 Ayu Icons](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu)
  - Simple theme with bright colors and comes in three versions (mainly using it for icons)
- [📦 Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  - Human-friendly comments in your code
- [📦 Bracket-padder](https://marketplace.visualstudio.com/items?itemName=viablelab.bracket-padder)
  - Smart whitespace padding & auto-closing for bracket pairs
- [📦 Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
  - Improve highlighting of errors, warnings and other language diagnostics
- [📦 Gruvbox Material](https://marketplace.visualstudio.com/items?itemName=sainnhe.gruvbox-material)
  - Gruvbox with Material Palette
- [📦 Hungry Delete](https://marketplace.visualstudio.com/items?itemName=jasonlhy.hungry-delete)
  - Delete an entire block of whitespace or tab
- [📦 TabOut](https://marketplace.visualstudio.com/items?itemName=albert.TabOut)
	- Tab out of quotes, brackets, etc
- [📦 TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
	- Highlight TODOs, FIXMEs, and any keywords, annotations...
- [📦 Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)
	- Automating the process of writing meaningful log messages
- [📦 Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
  - AI-assisted development

## Themes

J'utilise en général deux thèmes, un pour mes vidéos, un autre perso:

- Vidéos: Dark+ (thème) & Ayu (file icons)
- Perso: Gruvbox Material (thème) & Ayu (file icons)

La police que j'utilise dans les vidéos -> Consolas
La police que j'utilise personellement -> Iosevka

### Ancien thèmes perso

- Moxer Icons & Gruvbox Concoctis
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
	"gruvboxMaterial.darkContrast": "hard",
	"extensions.ignoreRecommendations": true,
	"explorer.confirmDragAndDrop": false,
	"workbench.sideBar.location": "right",
	"editor.suggestSelection": "first",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"[javascript]": {
			"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"git.enableSmartCommit": true,
	"git.autofetch": true,
	"editor.letterSpacing": 0.8,
	"[json]": {
			"editor.defaultFormatter": "vscode.json-language-features"
	},
	"editor.fontFamily": "Consolas",
	"editor.fontLigatures": false,
	"editor.fontSize": 14,
	"workbench.tree.indent": 10,
	"workbench.iconTheme": "ayu",
	"zenMode.centerLayout": false,
	"zenMode.hideLineNumbers": false,
	"explorer.compactFolders": false,
	"GitLive.Issue tracker integration": "Disabled",
	"workbench.statusBar.visible": false,
	"workbench.activityBar.visible": false,
	"liveServer.settings.donotShowInfoMsg": true,
	"todohighlight.keywords": [
		{
			"text": "NOTE:",
			"color": "#000",
			"backgroundColor": "aqua",
			"overviewRulerColor": "yellow",
		},
		{
			"text": "HACK:",
			"color": "#000",
		},
		{
			"text": "TODO:",
			"color": "red",
			"border": "1px solid red",
			"borderRadius": "2px", //NOTE: using borderRadius along with `border` or you will see nothing change
			"backgroundColor": "rgba(0,0,0,.2)",
			//other styling properties goes here ... 
		}
	],
	"go.toolsManagement.autoUpdate": true,
	"go.useLanguageServer": true,
	"errorLens.enabledDiagnosticLevels": [
		"warning",
		"info",
		"error"
	],
	"carbon.backgroundColor": "rgba(0,0,0,0)",
	"carbon.theme": "shades-of-purple",
	"carbon.dropShadow": false,
	"carbon.windowControls": false,
	"carbon.autoAdjustWidth": true,
	"carbon.fontFamily": "Hack",
	"[markdown]": {
		"editor.defaultFormatter": "yzhang.markdown-all-in-one"
	},
	"typescript.updateImportsOnFileMove.enabled": "always",
	"workbench.colorTheme": "Gruvbox Material Dark",
	"http.systemCertificates": false,
	"workbench.colorCustomizations": {},
	"window.zoomLevel": 2,
	"Lua.telemetry.enable": false
}
```

## License

[MIT](https://github.com/noxaled/gckn-pack/blob/master/LICENSE.txt)