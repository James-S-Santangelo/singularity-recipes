### Usage

```
singularity pull --name angsd.sif library://james-s-santangelo/ngsrelate/ngsrelate:2.0
singularity exec ngsRelate.sif ngsRelate [options]
```

See [ngsRelate](https://github.com/ANGSD/NgsRelate) for program documentation. 

**Note:** R is not presently installed in the container so accessory R scripts in ngsRelate/R/ will not work in the container.
