# PulseLite UI Sound Previewer

A static page with a mock game menu. Select Free sample, Menu Kit, Sci-Fi UI, or Horror UI. The free mode plays all 20 distinct free recordings; each paid style has three labelled listening samples from that pack. The page does not imply that every recording in a paid pack is auditioned here.

Choose a starting preview with the theme query parameter: <code>?theme=free</code>, <code>?theme=menu</code>, <code>?theme=scifi</code>, or <code>?theme=horror</code>. The player switches its sample set with the theme controls. Audio is loaded from sounds/free/ and the existing sounds/menu/, sounds/scifi/, and sounds/horror/ teaser folders.

## Packs

- **Free sample:** 20 distinct recordings; CC BY 4.0 audio and the free Godot 4 helper. MP3 and OGG files in the browser are alternate encodings, not additional recordings. Credit line: “Sounds: PulseLite UI SFX by Bigshadex (CC BY 4.0) https://bigshadex.itch.io/pulselite-ui-sfx-free”. [Free sample on itch.io](https://bigshadex.itch.io/pulselite-ui-sfx-free)
- **Menu Kit:** 200 recordings across 13 sound categories mapped to 14 named UI events (toggle has 8 on and 7 off sounds), WAV and OGG, plus Godot 4 and Unity helper scripts. The browser plays three teaser samples. https://bigshadex.itch.io/pulselite-ui-sfx
- **Sci-Fi UI:** 104 recordings across the same 14 named UI events, WAV and OGG, plus Godot 4 and Unity helper scripts. The browser plays three teaser samples. https://bigshadex.itch.io/pulselite-scifi-ui
- **Horror UI:** 104 recordings across the same 14 named UI events, WAV and OGG, plus Godot 4 and Unity helper scripts. The browser plays three teaser samples. https://bigshadex.itch.io/pulselite-horror-ui
- **PulseLite Complete:** the Menu, Sci-Fi, and Horror packs with 408 distinct recordings total (200 + 104 + 104). WAV and OGG are alternate formats, not extra recordings. https://bigshadex.itch.io/pulselite-complete

See itch.io for current prices and full licence terms. Paid downloads include Unity helper scripts that are compile-checked but have not been tested inside the Unity editor; they are not included in the free Godot repository. Paid teaser clips are for listening here and are not licensed for reuse.

The page uses local MP3/OGG assets, plain HTML/CSS/JavaScript, and no external libraries, frameworks, analytics, tracking, forms, or signups. The interface is an illustrative game-menu mockup, not an included game UI.

The audio is procedural DSP synthesis, not AI-generated audio. Scripts and page text were written with AI assistance. Page code is MIT.

Live page: https://bigshadex.github.io/pulselite-previewer/
Godot 4 add-on: https://github.com/BigShadex/pulselite-ui-godot

## Share card

`newassets/share-card.svg` is the editable source for `newassets/share-card.png`. The PNG was rendered from the SVG with the installed Microsoft Edge headless renderer at a 1200 × 630 viewport and verified as 1200 × 630; the artwork contains no audio or external images.
