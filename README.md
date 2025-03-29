Defrag Demo viewer
================

To run locally, create baseq3/ defrag/ and maps/ folders in the root, run a python server in the root:
```
~/gaem/ioq3 defrag-demo-viewer*
❯ ls baseq3
pak0.pk3              pak2.pk3              pak4.pk3              pak6.pk3              pak8.pk3              q3key                 zzz-safe-textures.pk3
pak1.pk3              pak3.pk3              pak5.pk3              pak7.pk3              q3config.cfg          zz-q3netpack.pk3

~/gaem/ioq3 defrag-demo-viewer*
❯ ls defrag
default.cfg                           zz-defrag_fix_shaders_190.pk3         zz-defrag_media_191.pk3               zzz-nade_flashing_green.pk3           zzz-standard_fonts_big_resolution.pk3 zzz-trigger-clip-clean-brush.pk3
zz-defrag_fix_mapscripts_190.pk3      zz-defrag_media_190.pk3               zz-defrag_vm_191.pk3                  zzz-no_teleport_effect.pk3            zzz-transparent_lagometer.pk3

~/gaem/ioq3 defrag-demo-viewer*
❯ ls maps
hgb-airbonk-1.pk3       hgb-tutte-vs-frutty.pk3

~/gaem/ioq3 defrag-demo-viewer*
❯ python3 -m http.server
```


Based on jdarpinian's emscripten work for ioq3 (https://github.com/jdarpinian/ioq3 )

Credits:
  * Quake III Arena [Buy the game!](https://store.steampowered.com/app/2200/Quake_III_Arena/)
  * [ioquake3](https://ioquake3.org)
  * [ZTM's Flexible HUD mod for ioquake3](https://github.com/zturtleman/flexible-hud-for-ioq3/)
  * [virtual-gamepad-lib](https://github.com/KW-M/virtual-gamepad-lib)
  * [compression-streams-polyfill](https://github.com/101arrowz/compression-streams-polyfill)
  * [jdarpinian/ioq3](https://github.com/jdarpinian/ioq3)
  * [Nosf's demo parser code](https://github.com/deniskond/dfcomps.ru)
