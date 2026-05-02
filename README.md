# HyprYou-VSCode-Theme
Applies HyprYou's colors to VS Code/VS Codium

# How to install
1. Make sure you have the m3e folder in ~/.vscode/extensions/
2. Symlink ~/.cache/hypryou/colors/colors.json to ~/.vscode/extensions/m3e/themes/colors.json using ```ln -s ~/.cache/hypryou/colors/colors.json ~/.vscode/extensions/m3e/themes/colors.json
3. Go to ~/.vscode/extensions/m3e/scripts and run ```node generate-theme.mjs``` in terminal
4. After that, apply the theme from VS Code/Codium
5. Enjoy!

# I have Windows/macOS/dont have HyprYou, what do i do?
The theme will do nothing. Really. You need HyprYou to get colors from the wallpapers and then install the theme.
If you are on Linux, you should refer to guide on HyprYou's GitHub. (though HyprYou isnt as much as stable it is on Arch Linux and its variatives!)

# I changed the wallpapers but colors didnt change
You gotta run the installation's step 3 and, if you had VS Code/Codium opened, restart it/reload window.
