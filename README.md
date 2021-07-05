# ladylike-linux
documentation of command line tools, WSL tricks, emacs configs, and other packages I like

## CLI tools
* **icdiff**: visual, side-by-side diff, [documentation here](https://www.jefftk.com/icdiff)
* **vtop**: graphical activity/processing monitor, [documentation here](https://github.com/MrRio/vtop)
* **carbon-now-cli**: automatically generated photos of your code so they can be easily shared, [documentation here](https://github.com/mixn/carbon-now-cli)
* **fzf**: fuzzy finder
* **ripgrep**: better grep
* **tree**: show file structure
* **bat**: better cat
* **tldr**: better man pages
* **exa**: better ls
* **wikit**: search wikipedia from terminal
* **thefuck**: correct things you forgot

## WSL tricks
* **Change machine name**: On WSL, you can't just edit `etc/hostname` and `etc/hosts`—first, you need to change it on Windows, using `System --> Change Settings --> Change`. Check if that worked with `sudo hostname wsl`. From there, follow [this](https://www.cyberciti.biz/faq/ubuntu-change-hostname-command/).

## Windows Terminal
* Check out `windows-terminal/settings.json` for my Windows Terminal settings as of March 2020. I'm currently using `colorScheme: killer-whale` but I've added a couple others that I like, so check them all out.
