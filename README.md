# YarnAce
Yarn (dialogue editor) syntax highlighting and theming for Ace (by Alec Holowka)

This is a convenience package separating out the Ace theme from https://github.com/InfiniteAmmoInc/Yarn

Credit for the original mode and theme files goes to Alec Holowka (InfiniteAmmoInc), Kyle J. Kemp (seiyria), and other Yarn contributors.

## Brace
I'm using this within a Webpack built application, hence I rely on the Brace fork of Ace that has been adapted for Browserify/Webpack. This requires a different syntax for the mode-yarn.js and theme-yarn.js files. Those changes live on the brace branch of this repo: https://github.com/RegisFrey/YarnAce/tree/brace (referenced in npm/yarn as https://github.com/RegisFrey/YarnAce#brace)

The main vanilla Ace branch hasn't been tested.
