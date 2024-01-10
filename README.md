# .ini Files for (F)All Out War

Back up your original .ini files and replace them with these.

These include the necessary tweaks to run mods as well as to enable logging for Buffout4. You will need to customize a few settings, I suggest using BethINI
however, you can set them manually.

These are the primary settings you may want to change (tweaked to balance performance on _my_ setup)

```toml
[Display]
iSizeW=6840
iSizeH=2160
[General]
bEnableRainOcclusion=0
bLensFlare=0
bReflectLODObjects=0
bReflectLODLand=0
bReflectSky=0
bReflectLODTrees=0
```

Maybe in the future, I will create other branches for different performance levels.

I would liked to have included a folder with MCM presets, but MCM does not seem to play nice with Steam on Linux in my current config for some reason. If you would like to contribute one, create a branch named feature/mcm-settings and upload your presets then create a Pull Request and I'll add them!
