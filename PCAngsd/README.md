### Usage

```
sigularity pull --name pcangsd.sif shub://James-S-Santangelo/singularity-recipes:pcangsd_v0.99
singularity shell pcangsd.sif
python3 /opt/pcangsd/pcangsd.py [options]
```

**note:** Recipe currently install latest version by cloning [PCAngsd GitHub repo](https://github.com/Rosemeis/pcangsd)
Latest version is 0.99 as of 2021-01-12. Could not use v0.98 due to Scipy issue (see [HERE](https://github.com/Rosemeis/pcangsd/issues/25)).

**TODO:** Change recipe to install v0.99 once tarball is released.

