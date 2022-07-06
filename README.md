# Data from Shirasawa et. al. (2017)

These data were downloaded from <http://sweetpotato-garden.kazusa.or.jp/> via the following script:

``` bash
wget ftp://ftp.kazusa.or.jp/pub/sweetpotato/GeneticMap/KDRIsweetpotatoXushu18S1LG2017.vcf.gz
```

However, it appears that the above links are now dead. These data have moved to Google Drive: <https://drive.google.com/file/d/1KCRx99esRC2OgCIyOBa4y7PrnhWofNYt/view?usp=sharing>

I am still posting the data here since I use it in a few of my papers (Gerard et al, 2018; Gerard and Ferrão, 2019; Gerard, 2021).

# How to download

Just run `wget`:

``` bash
wget https://github.com/dcgerard/KDRIsweetpotatoXushu18S1LG2017/raw/main/KDRIsweetpotatoXushu18S1LG2017.vcf.gz
```

You can unzip with `7z`

``` bash
7z e KDRIsweetpotatoXushu18S1LG2017.vcf.gz
```

# References

- D. Gerard. Double reduction estimation and equilibrium tests in natural autopolyploid populations. *bioRxiv*, 2021. doi: [10.1101/2021.09.24.461731](https://www.doi.org/10.1101/2021.09.24.461731).

- D. Gerard and L. F. V. Ferrão. Priors for genotyping polyploids. *Bioinformatics*, 36(6):1795–1800, 11 2019. ISSN 1367-4803. doi: [10.1093/bioinformatics/btz852](https://www.doi.org/10.1093/bioinformatics/btz852).

- D. Gerard, L. F. V. Ferrão, A. A. F. Garcia, and M. Stephens. Genotyping polyploids from messy sequencing data. *Genetics*, 210(3):789–807, 2018. ISSN 0016-6731. doi: [10.1534/genetics.118.301468](https://www.doi.org/10.1534/genetics.118.301468).

- K. Shirasawa, M. Tanaka, Y. Takahata, D. Ma, Q. Cao, Q. Liu, H. Zhai, S.-S. Kwak, J. C. Jeong, U.-H. Yoon, H.-U. Lee, H. Hirakawa, and S. Isobe. A high-density SNP genetic map consisting of a complete set of homologous groups in autohexaploid sweetpotato (*Ipomoea batatas*). *Scientific Reports*, 7, 2017. doi: [10.1038/srep44207](https://www.doi.org/10.1038/srep44207).
