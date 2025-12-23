There are a lot of great tools that already are preinstalled in Debian. Sometimes we do need something more, so here is a list of some of the tools preinstalled or not that I do use a lot.

Preinstalled tools:
1. Nano a simple text editor for editing text files and configuration files directly in the terminal
2. Some form of a GUI file explorer like Files on GNOME or Dolphin on KDE plasma
3. The default terminal like Terminal on GNOME or Konsole on KDE plasma
4. [[Apt Basics|apt]] the package manager 
5. A software store like Software which is a GUI for [[Apt Basics|apt]] could be useful but i find the command line easier
6. Bash which is the default shell is great for beginners

Tools I use a lot as a developer:
1. GIMP a great free open source alternative to photoshop 
2. Kitty a terminal emulator with very nice plaintext config files 
3. Hidamary a great way to set a live wallpaper on Debian for free https://github.com/jeffshee/hidamari
4. Flatpak a great way to install software that might not be available on apt but a bit less secure 
5. Neovim or nvim is a great text editor although a bit complex it is worth learning  here is a starter guide [[Neovim]] but you can also check ThePrimogen on YouTube.
6. zsh an alternative to bash that offers great plugin support

Here is a quick way to install these tools:
```bash
sudo apt install kitty zsh flatpak neovim gimp -y

sudo flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo

flatpak install flathub io.github.jeffshee.Hidamari
```
To me these tools are great for beginners and advanced users but of course do your own research and find what suits your workflow best. 