### Usage

```
singularity pull --name angsd.sif shub://James-S-Santangelo/singularity-recipes:ngsRelate_vlatest
singularity shell ngsRelate.sif
ngsRelate [options]
```

**Note:** This currently installs the latest version via the [ngsRelate GitHub Repo](https://github.com/ANGSD/NgsRelate)

**Note:** R is not presently installed in the container so accessory R scripts in ngsRelate/R/ will not work in the container.
