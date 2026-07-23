# TENGAI HIGH-LEVEL C++ / WASM

GitHub Pages artifact for the portable high-level Tengai port.

- The browser executable links only the platform-neutral HighLevelRuntime and tengai_core libraries.
- TengaiMachine, M68K/Z80 CPU backends and generated AOT instruction shards are not linked.
- Fixed-point trigonometry loads its typed table from math-data.bin.
- Source colors, frame-indexed cycles, diagnostic palettes, their stable-ID map, and the complete 161x8 stable-ID routing bank load from semantic palette-data.bin records.
- Sprite compositions, stable frame references, priority/orientation flags, the complete character-select roster/frame table, and typed renderer profile/scale/template/descriptor data load from semantic animation-data.bin records.
- Player movement, collision, shot formation and projectile animation profiles load from semantic projectile-data.bin records.
- Player lives, bomb inventory, hit/death/respawn rules and six stable character-bomb action roots load from semantic player-data.bin records.
- Scene selection, regional/world presentation and streamed-layer descriptors load from semantic presentation-data.bin records.
- Collision bounds, damage profiles and Q10 scaling curves load from semantic collision-data.bin records.
- The complete 15,314-command object-script catalog loads from object-actions.bin as address-free high-level actions with zero unclassified commands.
- Scene entry/update bindings and scene transitions load from address-free scene-flow-data.bin records.
- Stage scanline programs and raster segments load from semantic stage-scripts.bin records.
- Scheduled and streamed layer maps and their upload schedules load from semantic tilemap-data.bin records.
- Glyph advances, complete regional warning strings, reference tables and presentation layout load from semantic text-data.bin resources.
- Graphics load as standard indexed BMP atlases and the sprite LUT uses a typed BIN container.
- audio-program.bin, control-flow-data.bin and object-data.bin are retained only as typed migration evidence; the browser runtime does not execute them.
- No main/audio CPU program image or monolithic address-space substitute is loaded or published.
- Reference CPU, whole-system emulator and AOT compatibility cores are not linked.
- C/C++ source and lifting JSON are not published here.
- A built-in converted asset package is loaded automatically.
