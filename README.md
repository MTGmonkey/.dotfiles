# .dotfiles
simple NixOS dotfiles with flake. Fully modular and commented. Primarily TTU and CLI tools with a few real applications ig. As bare as possible
## Programs
every program has its own folder ./<name>/ with a file ./<name>/<name>.nix inside. Each <name>.nix is intended to be imported into [configuration.nix](configuration.nix). Any dotfiles associated with the program are also placed into ./<name>/ and properly linked to the <name>.nix. 
### [Vim](./vim/vim.nix)

### [XMonad](./xmonad/xmonad.nix)

