# TENGAI DIRECT C++ NATIVE

GitHub Pages production artifact for the portable Tengai port.

- 68EC020/Z80 addresses dispatch directly to generated C++ functions.
- Complete M68K reset and exception vectors load from board_profile.json.
- Fixed-point trigonometry loads its typed table from math-data.bin.
- Source colors, frame-indexed cycles, diagnostic palettes, their stable-ID map, and the complete 161x8 stable-ID routing bank load from semantic palette-data.bin records.
- Sprite compositions, stable frame references, priority/orientation flags, the complete character-select roster/frame table, and typed renderer profile/scale/template/descriptor data load from semantic animation-data.bin records.
- Player movement, collision, shot formation and projectile animation profiles load from semantic projectile-data.bin records.
- Scene selection, regional/world presentation and streamed-layer descriptors load from semantic presentation-data.bin records.
- Z80 driver tables, sound cue routing and music/effect sequences load from semantic audio-program.bin records.
- Collision bounds, damage profiles and Q10 scaling curves load from semantic collision-data.bin records.
- PC-relative indexed dispatches load as absolute target PCs from semantic control-flow-data.bin records.
- Object bytecode, typed parameters, callbacks and the complete function-selector dispatch load from object-data.bin.
- Stage scanline programs and raster segments load from semantic stage-scripts.bin records.
- Twenty scheduled/streamed layer maps and their upload schedules load from semantic tilemap-data.bin records.
- Glyph advances, complete regional warning strings, reference tables and presentation layout load from semantic text-data.bin resources.
- Graphics load as standard indexed BMP atlases; sprite LUT and YMF samples use typed BIN containers.
- No main/audio CPU program image or monolithic address-space substitute is loaded or published.
- Reference CPU and whole-system emulator cores are not linked.
- C/C++ source and lifting JSON are not published here.
- A built-in converted asset package is loaded automatically.
