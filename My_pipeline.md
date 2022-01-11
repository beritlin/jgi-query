# My pipeline

Downloading the genomes (protein sequneces)

```bash
python3 jgi-query.py Aaoar1 -r 'GeneCatalog_proteins.*\.aa.fasta.gz$'
```

Downloading the functions (GO)

```bash
python3 jgi-query.py Aaoar1 -r '_GO.*\.tab.gz$'
```
