<img width="468" height="15" alt="image" src="https://github.com/user-attachments/assets/c577aada-c6b5-4fbb-b09c-461eeaa94d45" /># earlyStageCRC
The study to seek the early-stage specific CRC signatures.

The software versions used in this study are written below.

# Softwares
| Tools | Versions | Options | Links | Others |
| ---| --- | --- | --- | --- |
|BLAST+|2.2.30|||16SrRNA gene detection with VITCOMIC2|
|mOTUs|3.0.3|max_tax, calc_mgc, calc_motu|https://github.com/motu-tool/mOTUs|ref_mOTU_3.0.3 meta_mOTU_3.0.3, for Taxonomic Profiling|
|MetaPhlAn 4|4.1.1|--index mpa_vJun23_CHOCOPhlAnSGB_202307 -t rel_ab_w_read_stats –add_viruses|https://github.com/biobakery/MetaPhlAn|for Taxonomic Profiling|
|AdapterRemoval|2.3.3|--identify-adapters|||
|bowtie2|2.2.9|--no-hd --no-sq --fast-local||Phix removal from shotgun metagenomic reads|
|seqkit|2.2.0|seq -m 50||length filtering|
|MEGAHIT|1.2.9|–min-contig-len 1500 parameter|||
|Flye|2.9.2-b1786|--pacbio-hifi|https://github.com/mikolmogorov/Flye||
|Prokka|1.14.6||https://github.com/tseemann/prokka||
|FastANI|1.33||https://github.com/ParBLiSS/FastANI||
|CheckM|1.2.0||https://github.com/Ecogenomics/CheckM||
|GTDB-Tk|2.1.1| classify_wf -x fa||release 207_v2 |
|dRep|2.3.2|dereplicate --S_ani 0.99 -comp 99 -con 1|https://github.com/MrOlm/drep||
|BLAST+|2.14.0|blastn -outfmt 6 -perc_identity 85 ||reference is publicly distributed from DDBJ[https://www.ddbj.nig.ac.jp/ddbj-releases-e.html], April 2023, including 1,399,781 sequences  Last published date in the present data: February 2023|
|barrnap|0.9||https://github.com/tseemann/barrnap||
|MetaPhlAn 4|4.1.1|||marker gene extraction ,mpa_vJun23_CHOCOPhlAnSGB_202403|
|Prokka|1.14.6| --compliant --rfam|https://github.com/tseemann/prokka|Preparetion of pseudogene detection|
|Unicycler|0.5.1||https://github.com/rrwick/Unicycler||
|Pseudofinder|1.14.6||https://github.com/filip-husnik/pseudofinder||
|DIAMOND| 0.9.10.111||https://github.com/bbuchfink/diamond||
|Panaroo|1.5.2||||
|samtools|1.19.2||||

# Python Packages
| Tools | Versions | Commands Options  | Others |
| ---| --- | --- | --- |
|SciPy|1.7.3||
|matplotlib-venn|v 0.11.9||
|clustal omega in Biopython|v 1.79 ||
