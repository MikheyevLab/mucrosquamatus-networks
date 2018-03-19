# _Protobothrops mucrosquamatus_ gene expression networks

## Data files
- `ercc.csv.gz` spike in controls
- `factors.csv` library description
- `rsem.csv.gz` rsem data on gene expression and gene names

You can donwload the pre-computed WGCNA results (strongly recommended, they take a long time) [here](https://www.dropbox.com/s/l1wpxnhjo8zqocw/wgcna.rds?dl=0). The script looks for them in the `data` folder

## To do

I don't think the chunk `module_trait` and anything below it works. There are good tutorials on the WGCNA website about how to conduct this type of analysis, particularly network preservation statistics. I strongly advise running those on Sango in parallel, and loading pre-computing results into RStudio, since they will take a long time, with lots of replicates.