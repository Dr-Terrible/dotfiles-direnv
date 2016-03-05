## Dr. Terrible's dotfiles

Dotfiles and system configuration files for [Direnv](https://github.com/direnv/direnv),
currently targetting OSX 10.11 (El Capitan) and GNU/Linux.

### Installation

Warning: If you want to give these dotfiles a try, you should first fork this repository,
review the code, and remove things you don't want or need. Don't blindly use my settings
unless you know what that entails. Use at your own risk!

```sh
$ bestow deploy ~/.config/dotter/dotfiles-direnv
Project: bestow
    ---> Build bestow in ./bin
bestow: Found a Bestow depot in ~/.config/dotter/dotfiles-direnv
bestow: Loading ~/.config/dotter/dotfiles-direnv/be.stow
bestow: pre-calculated checksum: 909871e.
bestow: I'm ready to roll out 1 dotfiles.
source: (string) (len=9) ".direnvrc"
comb: (string) (len=58) "/home/equilibrium/.config/dotter/dotfiles-direnv/.direnvrc"
destination: (string) (len=27) "/home/equilibrium/.direnvrc"
   ---> Task "direnv"       
  [NEW] symlink: ".direnvrc" -> "/home/equilibrium/.direnvrc"
bestow: Everything deployed as required.
```
