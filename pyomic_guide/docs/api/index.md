# User

Import Pyomic as:

```python
import Pyomic
```

## Bulk

|module|reference|
| ---- | ---- |
|[bulk.pyDEseq](bulk/api_deseq)|Different expression analysis|
|[bulk.enrichment](bulk/api_enrichment)|Geneset enrichment analysis|
|[bulk.tcga](bulk/api_tcga)|TCGA database preprocess|
|[bulk.network](bulk/api_network)|Protein-Protein interaction (PPI) analysis by String-db|
|[bulk.wgcna](bulk/api_module)|WGCNA (Weighted gene co-expression network analysis)|

## Single

|module|reference|
| ---- | ---- |
|[single.SCSA](single/api_scsa)|Celltype annotation with SCSA|
|[single.COSG](single/api_cosg)|Marker genes filtered with COSG|
|[single.scDrug](single/api_scdrug)|Drug response predict with scDrug|
|[single.scGSEA](single/api_scgsea)|Pathway analysis with AUCell|
|[single.cpdb](single/api_cpdb)|Cell interaction with CellPhoneDB|
|[single.MOFA](single/api_mofa)|Multi omics analysis by MOFA|

## Bulk2Single

|module|reference|
| ---- | ---- |
|[bulk2single.Bulk2Single](bulk2single/api_bulk2single)|Bulk RNA-seq to Single RNA-seq|