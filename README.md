# dotfiles
A fresh dotfiles repo

## To-do list

- zsh
 - something around oh-my-zsh
 - separate these three:
  - oh-my-zsh config
  - "general" .zshrc stuff
  - machine-local zshrc stuff (Mercury)
 - merge zprofile and mercury zshrc stuff

- vim
 - pick a plugin manager, maybe pathogen to start with it seems minimal
 - find some appropriate plugins
  - ctrlp
 
- tmux
 - decide on some tmux bindings and prefixes
  - c-s-hjkl for navigating panes
  - a-s-hl for windows?
  - what's a good prefix combo? c-b collides with vim
   - c-, might be good
 - get the layout right and use it by default

- git
 - strip out mercury stuff, put the rest in dotfiles
 - can I compose .gitconfig files? oh there's [includeIf], that's neat
  https://stackoverflow.com/questions/64843104/why-gitconfig-includeif-does-not-work
  https://dzone.com/articles/how-to-use-gitconfigs-includeif
  https://medium.com/@mrjink/using-includeif-to-manage-your-git-identities-bcc99447b04b
  or just [include] I guess

- dotfiles
 - idk probably use dotbot, chezmoi is too opinionated
 - organize stuff
