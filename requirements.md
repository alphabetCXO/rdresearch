## 1. 安装perl(支持多线程)
`./Configure -des -Dprefix=/usr/local/perl -Dusethreads`  

## Tools  
* perl==`5.18.1`  
>  threads-2.01.tar.gz  
>  Crypt-RC4-2.02.tar.gz  
>  DBD-SQLite-1.13.tar.gz  
>  DBI-1.631.tar.gz  
>  Digest-Perl-MD5-1.9.tar.gz  
>  Excel-Writer-XLSX-0.83.tar.gz  
>  OLE-Storage_Lite-0.19.tar.gz  
>  Spreadsheet-ParseExcel-0.65.tar.gz  
>  Spreadsheet-WriteExcel-2.40.tar.gz  

java>=1.7.0_45

* R  
> forest  

fastqc

bwa==0.7.10
  bwa7ucsc19ref
  
samtools==0.1.19
  samtools0119ucsc19ref_index
  
gatk>=3.3-0

bundle_28_hg19

picardtools==1.117

SOAPnuke

soap
  soap2ucsc19ref
  soap2ucsc19ref_index
  
soapsnp
  soapsnp_dbsnp_dir
  soapsnp_ref_dir
  
Platypus

VEP==77
  ensembl_cache

bcftools

vcf_concat

bgzip

tabix

## Data
ref
bed
freq
GO_KEGG
GWAVA_score
harmful_score
in_house
dbNSFP
