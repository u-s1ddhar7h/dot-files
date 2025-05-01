# Dot-Files
I'm using NixOS(stable) ❄️ as my daily driver and GNU-Stow to manage the dot-files  🙂 

#### Setup Instruction ...
1. Remove/Delete all config directory/files that you intend to stow next.
2. Go to your Stow directory (in my case remote-repository `dot-files`).
3. Run the `stow` command with package that you want to stow.
example: `stow -v -t ~ nvim`.
4. If you want to all the packages at once run: `stow -v -t ~ .`.
5. All set!
