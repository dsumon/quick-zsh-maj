# quick-zsh MAJ
A simple script to setup an awesome shell environment.
Quickly install and setup zsh and oh-my-zsh (https://github.com/robbyrussell/oh-my-zsh) with
* Dallas theme
* zsh-completions (https://github.com/zsh-users/zsh-completions)
* zsh-autosuggestions (https://github.com/zsh-users/zsh-autosuggestions)
* zsh-syntax-highlighting (https://github.com/zsh-users/zsh-syntax-highlighting)
* history-substring-search (https://github.com/zsh-users/zsh-history-substring-search)
* fzf (https://github.com/junegunn/fzf)
* k (https://github.com/supercrabtree/k)
* marker (https://github.com/pindexis/marker)

Sets following useful aliases:
* l="ls -lah"         - just type "l" instead of "ls -lah"
* alias k="k -h"	  - show human readable filesizes, in kb, mb etc
* https               - make httpie use https
* myip - (wget -qO- https://wtfismyip.com/text)       - what's my ip: quickly find out external IP
* cheat - (https://github.com/chubin/cheat.sh)        - cheatsheets in the terminal!
* ipgeo - (curl "http://api.db-ip.com/v2/free/$1")    - finds geo location from IP

## Installation
Requirements:
* `git` to clone it.
* `python3` or `python` is required to run option '-c' which copies history from .bash_history

``` bash
git clone https://github.com/dsumon/quick-zsh-maj.git
cd quick-zsh-maj
sudo chmod +x quickz.sh
./quickz.sh -c        # only run with '-c' the first time, running multiple times will duplicate history entries
```

Source: https://github.com/jotyGill/quickz-sh
