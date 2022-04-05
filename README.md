# getCodingKnowledge Extension Pack

getCodingKnowledge Extension Pack est une collection des extensions que j'utilise sur [mes différentes vidéos](https://www.youtube.com/c/getcodingknowledge).

## Extensions inclus

En installant mon pack, ces extensions seront installées:

- [📦 .gitignore Generator](https://marketplace.visualstudio.com/items?itemName=piotrpalarz.vscode-gitignore-generator)
  - Generate .gitignore file using gitignore.io API
- [📦 AI Doc Writer](https://marketplace.visualstudio.com/items?itemName=mintlify.document)
  - AI powered documentation writer
- [📦 Bracket-padder](https://marketplace.visualstudio.com/items?itemName=viablelab.bracket-padder)
  - Smart whitespace padding & auto-closing for bracket pairs
- [📦 Code Metrics](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-codemetrics)
  - Computes complexity in TypeScript / JavaScript files.
- [📦 Community Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-community-material-theme)
  - The official community maintained Material Theme with 'legacy' color schemes you love!
- [📦 Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
  - Improve highlighting of errors, warnings and other language diagnostics
- [📦 Hungry Delete](https://marketplace.visualstudio.com/items?itemName=jasonlhy.hungry-delete)
  - Delete an entire block of whitespace or tab
- [📦 Material Theme Icons](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme-icons)
  - Material Theme Icons, the most epic icons theme for Visual Studio Code and Material Theme.
- [📦 TabOut](https://marketplace.visualstudio.com/items?itemName=albert.TabOut)
	- Tab out of quotes, brackets, etc
- [📦 Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
  - AI-assisted development

## Themes

J'utilise en général deux thèmes, un pour mes vidéos, un autre perso:

- Vidéos: Dark+ (thème) & Ayu (file icons)
- Perso: Community Material Theme Darker High Contrast (thème) & Material Theme Icons (icones)
La police que j'utilise dans les vidéos -> Consolas
La police que j'utilise personellement -> Iosevka

### Ancien thèmes perso

- Gruvbox Material (thème) & Ayu (file icons)
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
	"explorer.confirmDelete": false,
	"extensions.ignoreRecommendations": true,
	"explorer.confirmDragAndDrop": false,
	"workbench.sideBar.location": "right",
	"editor.suggestSelection": "first",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"editor.fontFamily": "Consolas",
	"editor.fontLigatures": false,
	"editor.fontSize": 14,
	"workbench.tree.indent": 10,
	"workbench.iconTheme": "eq-material-theme-icons",
	"zenMode.centerLayout": false,
	"zenMode.hideLineNumbers": false,
	"explorer.compactFolders": false,
	"workbench.statusBar.visible": false,
	"workbench.activityBar.visible": false,
	"go.toolsManagement.autoUpdate": true,
	"go.useLanguageServer": true,
	"errorLens.enabledDiagnosticLevels": [
		"warning",
		"info",
		"error"
	],
	"typescript.updateImportsOnFileMove.enabled": "always",
	"http.systemCertificates": false,
	"workbench.colorCustomizations": {},
	"window.zoomLevel": 1,
	"Lua.telemetry.enable": false,
	"editor.inlineSuggest.enabled": true,
	"workbench.colorTheme": "Community Material Theme Darker High Contrast"
}
```

## License

[MIT](https://github.com/noxaled/gckn-pack/blob/master/LICENSE.txt)