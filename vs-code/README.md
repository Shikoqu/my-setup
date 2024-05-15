# My VS Code setup

---

## Extensions
You can view a full list of my extensions [here](my-extensions.md).

I use multiple languages so it's quite a lot of them here. Feel free to snatch some of them, however i do not recommend installing all of them at once.  

If anyone wonders how to make such a list yourself, I will drop this command for you:

```zsh
code --list-extensions
```

### Recommendations
1. Best color theme in the world!
   - [catppuccin](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc)
   - [catppuccin-icons](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc-icons)

1. Color-coded comments
   - [better-comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

1. Pretty markdown
   - [markdown-preview-enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

1. Beautiful screenshots of code
   - [codesnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)

1. AI assistant (other than coplot)
   - [codeium](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium)

---

## Settings
Take a look at my settings.json file [here](settings.jsonc).

Again... I do not recommend to copy this one to one. you can take inspiration from myy settings however this topic is really subjective.

### Recommendations
1. Get code snippets at the top of suggestion dropdown
    ```json
    "editor.snippetSuggestions": "top",
    "editor.suggestSelection": "first",
    ```

1. Maximize workspace area
    ```json
    "workbench.editor.editorActionsLocation": "titleBar",
    "workbench.editor.showTabs": "none",
    "workbench.activityBar.location": "top",
    "workbench.statusBar.visible": false,
    "workbench.layoutControl.enabled": false,
    ```

1. Make the most of your terminal (with Nerd Font)
   ```json
   "terminal.integrated.fontFamily": "'Fira Code', 'MesloLGS NF'",
   ```
   I use primarily [Fira Code](https://fonts.google.com/specimen/Fira+Code) font, but as a fallback for more glyphs some Nerd Font like [MesloLGS NF](https://github.com/romkatv/dotfiles-public/tree/master/.local/share/fonts/NerdFonts) is good.