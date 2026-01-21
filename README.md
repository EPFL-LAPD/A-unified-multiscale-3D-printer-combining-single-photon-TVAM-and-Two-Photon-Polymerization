# A unified multiscale 3D printer combining single-photon Tomographic Volumetric Additive Manufacturing and Two-Photon Polymerization
## Buse Unlu, Felix Wechsler, Ye Pu, Christophe Moser
### Laboratory of Applied Photonics Devices, School of Engineering, Ecole Polytechnique Fédérale de Lausanne, CH-1015, Lausanne, Switzerland

The pre-print of this work is available under: [https://arxiv.org/abs/2601.13457](https://doi.org/10.48550/arXiv.2601.13457)

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


## Citation 
Please consider citing this work:
```bibtex
@misc{unlu2026unifiedmultiscale3dprinter,
      title={A unified multiscale 3D printer combining single-photon Tomographic Volumetric Additive Manufacturing and Two-Photon Polymerization}, 
      author={Buse Unlu and Felix Wechsler and Ye Pu and Christophe Moser},
      year={2026},
      eprint={2601.13457},
      archivePrefix={arXiv},
      primaryClass={physics.optics},
      url={https://arxiv.org/abs/2601.13457}, 
}
```

## License
The following configuration files are compatible with [Dr.TVAM](https://github.com/rgl-epfl/drtvam) and are only allowed to use for academic, non-commercial purposes only. See [LICENSE](LICENSE) for more details.
