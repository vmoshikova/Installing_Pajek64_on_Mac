Pajek64 for macOS

1. First, you need to install it using your Terminal by running this command:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)”

3. Then, you need to install Cask by runing:

brew install caskroom/cask/brew-cask

5. You need to move the Pajek64 folder to Applications (you can do this by dragging and dropping or in the Terminal)

% mv ~/Downloads/Pajek64 ~/Applications/Pajek64

7. Now, you can install wine:

brew install wine-stable

9. Now, you can open Wine and enter:
   
wine64 /Applications/Pajek64/Pajek.exe

11. You are amazing!
