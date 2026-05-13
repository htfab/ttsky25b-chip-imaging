## Tiny Tapeout Sky 25B tile map

➡️ [View TTSky25B tile map](https://htfab.github.io/ttsky25b-chip-imaging/#url=data/ttsky25b.json)

GDS and local interconnect (LI) were rendered using [tinytapeout-chip-renders](https://github.com/TinyTapeout/tinytapeout-chip-renders/) at a scale of 5:

```
$ cd tinytapeout-chip-renders/scripts
$ python render.py ttsky25b --scale 5
```

They were then sliced using the [GroupXIV slicer](https://github.com/whitequark/groupXIV).
