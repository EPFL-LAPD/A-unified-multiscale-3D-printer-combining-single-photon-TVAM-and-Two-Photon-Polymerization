# A unified multiscale 3D printer combining single-photon Tomographic Volumetric Additive Manufacturing and Two-Photon Polymerization
## Buse Unlu, Felix Wechsler, Ye Pu, Christophe Moser


## Running of code
The TVAM patterns have been optimized with [Dr.TVAM](https://github.com/rgl-epfl/drtvam).
Preferrably, install Dr.TVAM on a CUDA accelerated computer:
```bash
pip install drtvam==0.7.0
```

Run the optimization with
```bash
drtvam gear/config.json
drtvam prisms/config.json
```
