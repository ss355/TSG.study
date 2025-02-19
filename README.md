# TSG.study
The README file for genes identified by Methods A, B, C. and D in our Tumor Supressor Gene (TSG) methylation study

The corresponding R code and Input to obtain the gene list in "Gene.Lists.TEXT" folder 
are saved in the "R.Code.and.Input" folder. 

#################################################################################################
#################################################################################################
# In the "Gene.Lists.TEXT" folder, we included the lists of genes identified by all 4 methods 
# (Methods A, B, C, and D), see the number of genes and file names below. 
# The first 4 files have all the genes shown in the Table 6. 
# The line number is the TOTAL number of genes shown in Table 6 last column, for example, 
# "25 Feb15.2025.BRCA.TSG.methodA.gene.list.txt" means that 24 genes + 1 header (or column names)

# Folder: Gene.Lists.TEXT

wc -l *.txt

# TSG and non-TSG genes identified by method A and B, as summarized in Table 6 
      25 Feb15.2025.BRCA.TSG.methodA.gene.list.txt
     243 Feb15.2025.BRCA.TSG.methodB.gene.list.txt
     707 Feb15.2025.BRCA.nonTSG.methodA.gene.list.txt
    5344 Feb15.2025.BRCA.nonTSG.methodB.gene.list.txt

# TSG and non-TSG genes identified by method C
      34 Feb15.2025.BRCA.TSG.methodC.gene.list.txt
      69 Feb15.2025.BRCA.nonTSG.methodC.gene.list.txt

# TSG and non-TSG genes identified by method D
      31 Feb15.2025.BRCA.TSG.methodD.gene.list.txt
      93 Feb15.2025.BRCA.nonTSG.methodD.gene.list.txt

#################################################################################################
#################################################################################################
# For more detailed co-methylation change of these genes, see the following individual folders. 
# In each folder, in addition to have a CSV file, we also have an EXCEL version each gene list
# to make it easy for readers to click to open the gene list file. 

# Table 6 genes in detail:

# In the "Method_A.Table6.Row1and3" and "Method_B.Table6.Row2and4", we have lists of the 
# separate/individual gene list shown in each cell of Table 6.
# We provided both CSV and EXCEL version of these individual genes. See detailed 

Table 6 Counts:

Method A - TSG counts:

These counts correspond to the 1st row of Table 6 and are listed in order of the columns. 
That is,the first count for the file  "Aug12.2022.onlyTSG.overlap.neg2pos.only.alive.genes.freq3.csv" 
corresponds to the 1st column of the 1st row, "Aug12.2022.onlyTSG.overlap.pos2neg.only.alive.genes.freq3.csv"
is the 2nd column, and so on. Each line of the files contain one gene, so the total number of lines in each file is the number of genes plus 1. 

All of the counts are off by one because these file include the headers, which are being counted as separate lines. 

[c_t370@login1 gene_from_diff_methods]$ pwd 
Folder: /Method_A.Table6.Row1and3/TSG
 wc -l *csv
  2 Aug12.2022.onlyTSG.overlap.neg2pos.only.alive.genes.freq3.csv
  1 Aug12.2022.onlyTSG.overlap.pos2neg.only.alive.genes.freq3.csv
  3 Aug12.2022.onlyTSG.overlap.sleeping.neg.only.alive.genes.freq3.csv
  1 Aug12.2022.onlyTSG.overlap.sleeping.pos.only.alive.genes.freq3.csv
 21 Aug12.2022.onlyTSG.overlap.shutting.neg.only.alive.genes.freq3.csv
  2 Aug12.2022.onlyTSG.overlap.shutting.pos.only.alive.genes.freq3.csv


Method A - non-TSG counts:

These counts correspond to the 3rd row of Table 6 and are listed in order of the columns. That is,the first count for the file 
"Aug12.2022.nonTSG.Overlap.neg2pos.only.alive.genes.freq3.csv" corresponds to the 1st column of the 3rd row, "Aug12.2022.nonTSG.Overlap.pos2neg.only.alive.genes.freq3.csv"
is the 2nd column, and so on. Each line of the files contain one gene, so the total number of lines in each file is the number of genes plus 1. 
All of the counts are off by one because these file include the headers, which are being counted as separate lines. 

Folder: /Method_A.Table6.Row1and3/non_TSG
wc -l *csv
   5 Aug12.2022.nonTSG.Overlap.neg2pos.only.alive.genes.freq3.csv
   6 Aug12.2022.nonTSG.Overlap.pos2neg.only.alive.genes.freq3.csv
   6 Aug12.2022.nonTSG.Overlap.sleeping.neg.only.alive.genes.freq3.csv
  21 Aug12.2022.nonTSG.Overlap.sleeping.pos.only.alive.genes.freq3.csv
 606 Aug12.2022.nonTSG.Overlap.shutting.neg.only.alive.genes.freq3.csv
  68 Aug12.2022.nonTSG.Overlap.shutting.pos.only.alive.genes.freq3.csv
  
#################################################################################################
Method B - TSG counts:

These counts correspond to the 2nd row of Table 6 and are listed in order of the columns the same way that the files in the previous section are. 

Folder: Method_B.Table6.Row2and4/TSG

 wc -l *csv
  12 Aug12.2022.onlyTSG.overlap.neg2pos.only.dead.genes.freq3.csv
  18 Aug12.2022.onlyTSG.overlap.pos2neg.only.dead.genes.freq3.csv
  50 Aug12.2022.onlyTSG.overlap.sleeping.neg.only.dead.genes.freq3.csv
  82 Aug12.2022.onlyTSG.overlap.sleeping.pos.only.dead.genes.freq3.csv
  24 Aug12.2022.onlyTSG.overlap.shutting.neg.only.dead.genes.freq3.csv
  62 Aug12.2022.onlyTSG.overlap.shutting.pos.only.dead.genes.freq3.csv

Method B - non-TSG counts:

These counts correspond to the 4th row of Table 6 and are listed in order of the columns the same way that the files in the previous section are. 

Folder: Method_B.Table6.Row2and4/non_TSG

wc -l *csv
   39 Aug12.2022.nonTSG.Overlap.neg2pos.only.dead.genes.freq3.csv
  124 Aug12.2022.nonTSG.Overlap.pos2neg.only.dead.genes.freq3.csv
  602 Aug12.2022.nonTSG.Overlap.sleeping.neg.only.dead.genes.freq3.csv
 2289 Aug12.2022.nonTSG.Overlap.sleeping.pos.only.dead.genes.freq3.csv
  101 Aug12.2022.nonTSG.Overlap.shutting.neg.only.dead.genes.freq3.csv
 2194 Aug12.2022.nonTSG.Overlap.shutting.pos.only.dead.genes.freq3.csv

#################################################################################################
Method C - TSG and non-TSG gene list 
Folder: Method C 
wc -l *.csv   

      34 Aug23.2022.onlyTSG.overlapgenes.in.alive.dead.panels4.freq3.csv
      69 Aug23.2022.nonTSG.Overlapgenes.in.alive.dead.panels4.freq3.csv

#################################################################################################
Method D - TSG and non-TSG gene list 
Folder: Method D 

wc -l *.csv
      31 Aug23.2022.onlyTSG.overlapgenes.in.alive.dead.panels4.freq.diff3.csv
      93 Aug23.2022.nonTSG.Overlapgenes.in.alive.dead.panels4.freq.diff3.csv





