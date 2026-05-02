# HyprYou-VSCode-Theme
Applies HyprYou's colors to VS Code/VS Codium

# How to install
* For Codium, the path is ~/.vscode-oss/extensions/m3e/...
1. (if not done) Install node using ```sudo pacman -S node```
2. Make sure you have the m3e folder in ~/.vscode/extensions/ (move it there if you havent)
3. Symlink ~/.cache/hypryou/colors/colors.json to ~/.vscode/extensions/m3e/themes/colors.json using ```ln -s ~/.cache/hypryou/colors/colors.json ~/.vscode/extensions/m3e/themes/colors.json```
4. Go to ~/.vscode/extensions/m3e/scripts and run ```node generate-theme.mjs``` in terminal
5. After that, apply the theme (name: Material 3 Expressive) from VS Code/Codium
6. Enjoy!
7. (optional) Symlink ~/.vscode/extensions/m3e/scripts/generate-theme.mjs to any place you are comfortable with using ```ln -s ~/.vscode/extensions/m3e/scripts/generate-theme.mjs (somewhere you want)```

# I have Windows/macOS/dont have HyprYou, what do i do?
This theme will not work. It depends on HyprYou’s color output system.
If you are on Linux but don’t use HyprYou, refer to its GitHub documentation. (on github.com/koeqaife/hyprland-material-you)

# I changed the wallpapers but colors didnt change
You gotta run the installation's step 3 and, if you had VS Code/Codium opened, restart it/reload window. Its because the theme isnt using the colors.json file since its format is invalid for VS Code/Codium and the script isnt automatic (you can automate it though).
