# Aurora particle editor

A browser editor for the Aurora particle scripts of Syndicate Black Ops (`aurora/*.aur`, used by the `env_particle`
entity)

Open it: https://syndicate-black-ops.github.io/aurora-editor/

- Open a shipped script or a template, edit it in a form or as text, and watch it run
- The preview is the game's own particle code compiled to WebAssembly, so it behaves as in game
- Download the `.aur`, or a zip with `aurora/` and `sprites/` laid out as in the game folder
- Your uploaded `.spr` and `.aur` files and your drafts stay in your browser; nothing is sent to a server

## This repository

The site lives on the `gh-pages` branch and is generated from the game's source: the game repository builds it
(`tools/aurora-editor/publish.sh`) and pushes the result there. Changes to the editor belong in the game repository,
not here

Half-Life's particle sprites on the site are Valve's files, from Half-Life
