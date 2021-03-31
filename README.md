# test-datasets: NA12878 / C57BL_6NJ

This dataset comprises both human (NA12878) and mouse (C57BL_6NJ) reads:

* The NA12878 data consists of 150 bp paired-end reads which appear to align to human chromosome 19.

```
samtools view \
    -b \
    -o NA12878.chr19.bam \
    ftp://ftp.sra.ebi.ac.uk/vol1/run/ERR323/ERR3239334/NA12878.final.cram \
    chr19
```

* The C57BL_6NJ readgroups consist of a mix of 100 bp and 125 bp paired-end reads which appear to align to mouse chromosome 19.

```
samtools view \
    -b \
    -o C57BL_6NJ.chr19.bam \
    ftp://ftp-mouse.sanger.ac.uk/current_bams/C57BL_6NJ.bam \
    19
```

## Links

* [Data collections for NA12878](https://www.internationalgenome.org/data-portal/sample/NA12878)
* [The Mouse Genomes Project ](https://www.sanger.ac.uk/data/mouse-genomes-project)
