## Vim setup

This repository was created to easily download my setup for the **Vim text-editor** whenever I reinstall/change my device.

The installed modules in it are created as submodules from another repositories so if there is an update they can be easily "*git pull*"-ed.

### Instalation:

Just clone this repository to your "/home/{username}/" folder and you are good to go. 

For newbies there is a step-by-step instalation guide below:

1. (*Optional*) Install **vim** and **git** if you don't have them:
- Debian based OS: ``` sudo apt install vim git ```
- Arch based OS: ``` pacman -S vim git```
- Fedora OS: ``` sudo dnf install vim git```

2. Go to your home folder:

```
cd
```
3. Clone the repository:
``` 
git clone https://github.com/skuzol/.vim.git
```
4. Download all submodules of the repository:
```
cd ~/.vim
git submodule init
git submodule update
```
5. Enjoy!
