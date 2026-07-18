# TENGAI DIRECT C++ NATIVE

GitHub Pages production artifact for the portable Tengai port.

- 68EC020/Z80 addresses dispatch directly to generated C++ functions.
- Fixed-point trigonometry loads its typed table from math-data.bin.
- Source colors load from semantic palette-data.bin records.
- Sprite compositions and stable frame references load from semantic animation-data.bin records.
- Collision bounds and object damage profiles load from semantic collision-data.bin records.
- Object bytecode tokens, typed parameters and dispatch metadata load from object-data.bin.
- Stage scanline programs and raster segments load from semantic stage-scripts.bin records.
- Scheduled/streamed layer maps and upload schedules load from semantic tilemap-data.bin records.
- Glyph advances and diagnostic strings load from semantic text-data.bin resources.
- Graphics load as standard indexed BMP atlases; other assets are BIN files.
- Reference CPU and whole-system emulator cores are not linked.
- C/C++ source and lifting JSON are not published here.
- A built-in converted asset package is loaded automatically.
