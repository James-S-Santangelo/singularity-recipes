### Usage

```
singularity pull --name clumpak.sif library://james-s-santangelo/clumpak/clumpak:1.1
singularity exec clumpak.sif perl /opt/bin/BestKByEvanno.pl [options]
```

**Note:** Only the `BestKByEvanno.pl` pipeline is currently working. The others are failing 
due to a path issue with `CLUMPP` and maybe `distruct`. Might fix at one point. 
