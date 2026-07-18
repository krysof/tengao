# TENGAI DIRECT C++ NATIVE

GitHub Pages production artifact for the portable Tengai port.

- 68EC020/Z80 addresses dispatch directly to generated C++ functions.
- Complete M68K reset and exception vectors load from board_profile.json.
- Fixed-point trigonometry loads its typed table from math-data.bin.
- Source colors and frame-indexed palette cycles load from semantic palette-data.bin records.
- Sprite compositions, stable frame references and priority layer masks load from semantic animation-data.bin records.
- Collision bounds, damage profiles and Q10 scaling curves load from semantic collision-data.bin records.
- PC-relative indexed dispatches load as absolute target PCs from semantic control-flow-data.bin records.
- Object bytecode, typed parameters, callbacks and the complete function-selector dispatch load from object-data.bin.
- Stage scanline programs and raster segments load from semantic stage-scripts.bin records.
- Scheduled/streamed layer maps and upload schedules load from semantic tilemap-data.bin records.
- Glyph advances and diagnostic strings load from semantic text-data.bin resources.
- Graphics load as standard indexed BMP atlases; other assets are BIN files.
- Reference CPU and whole-system emulator cores are not linked.
- C/C++ source and lifting JSON are not published here.
- A built-in converted asset package is loaded automatically.
