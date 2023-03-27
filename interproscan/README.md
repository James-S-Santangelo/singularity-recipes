### Usage

```
singularity pull --name interproscan.sif library://james-s-santangelo/interproscan/interproscan:5.61-93.0
singularity exec --bind interproscan-data-5.61-93.0/data:/opt/interproscan-5.61-93.0/data interproscan.sif interproscan.sh [options]
```

Note the container does not contain the data required to run interproscan
The data can be downloaded by running the following commands:

```
wget https://ftp.ebi.ac.uk/pub/software/unix/iprscan/5/5.61-93.0/alt/interproscan-data-5.61-93.0.tar.gz
wget https://ftp.ebi.ac.uk/pub/software/unix/iprscan/5/5.61-93.0/alt/interproscan-data-5.61-93.0.tar.gz.md5
md5sum -c interproscan-data-5.61-93.0.tar.gz.md5
tar -pxvzf interproscan-data-5.61-93.0.tar.gz
chmod -R 777 interproscan-data-5.61-93.0
```

The resulting untared data folder then needs to beb bound to the container at runtime as above

See [Interproscan](https://interproscan-docs.readthedocs.io/en/latest/) for program documentation.
