# PulseLite UI Sound Previewer

A small static web page: click through a mock game menu and hear the 20 free PulseLite UI sounds, or pick a paid style (Menu Kit, Sci-Fi, Horror) to hear a 3-sound preview of that pack only.

Link straight to a style with `?theme=free|menu|scifi|horror` (e.g. `?theme=horror`). Prices and the sale end date live in the `CONFIG` object at the top of the script in `index.html`. No analytics or tracking.

Live: https://bigshadex.github.io/pulselite-previewer/

- Free sounds (`sounds/free/`): CC BY 4.0. Credit: `Sounds: PulseLite UI SFX by Bigshadex (CC BY 4.0) https://bigshadex.itch.io/pulselite-ui-sfx-free`
- Teaser sounds (`sounds/menu|scifi|horror/`): from the paid packs, included for preview only, not licensed for reuse. Get them at https://bigshadex.itch.io/pulselite-complete
- Page code: MIT. Written with AI assistance. Audio is procedural DSP synthesis, not AI-generated.
- Godot 4 addon: https://github.com/BigShadex/pulselite-ui-godot
