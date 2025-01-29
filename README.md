# High-Throughput-Data-Analysis

This repository contains all the assignments for the Computational Methods for the High-Throughput- Data analysis course. Each assignment is organized into its own folder, which includes the input files, code, and output files, structured within their respective directories.

### Assignment-1
1. Programming Language and Version: Python and Python 3.11.4.

2. Dependencies: Python Libraries. NumPy, Pandas, Seaborn.

3. Input: matrix1.txt, matrix2.txt.

4. Description: This python code generates a 12x12 Pearson correlation matrix from RPKM across various cancers in a specific patient group, using "matrix1.txt" and "matrix2.txt" files using python packages such as Numpy and Pandas. It visualizes the generated matrix as a heatmap to highlight similarities between cancers using various Python Visualization Packages such as Seaborn. Finally, the code computes a Pearson correlation between both the original matrices.

5. Execution Clone the repository. Download matrix1.txt, matrix2.txt. Run the Assignment_1.ipynb file. Check the output.

6. Output: Each value of the pearson correlation between two variables of the original matrices are shown in the Heatmaps.

### Assignment-2
1. Programming Language and Version: Python and Python 3.11.4.

2. Dependencies: Python Libraries. NumPy, Pandas, Seaborn, SciPy

Input: DecayTimecourse.txt

3. Description: First the python code changes the .txt original file to .csv and then the python code calculates the half lifes of the genes in three time courses and also calculates the final half-life which is the average of the half-lifes of three time courses by handling the missing values (NaN Values) and saves the result into a .csv file. After calculating the final half-life, the code will give the outputs of (half_lifes) top 10% and bottom 10% of genes and saves them into two sepearate .csv files.(The output .csv file names are mentioned in the Output section).

4. Execution Clone the repository. Download DecayTimecourse.txt. Run the Assignment -2_Half_Lives.ipynb file. Check the output.

5. Output: After running the code with the Download DecayTimecourse.txt. The output files include 1. DecayTimecourse.csv ('After Converting the DecayTimecourse.txt' to .csv) 2. half_life_results.csv (After Calculating the half-life for all the three time courses and final half_life which is average of half_life of three time courses) 3. very_low_half_lives.csv ( Contains bottom 10% of genes with low half lives) 4. very_high_half_lives.csv ( Contains Top 10% of genes with high half lives). All these files are included in the repository for references.

6. Functional_Enrichment_Analysis: Using the provided link to perform the simple functional enrichment analysis. The output files (.png) of the analysis are included in the repository.

### Assignment-3
1. Programming Language and Version: Python and Python 3.11.4.

2. Dependencies: Python Libraries. Pandas.

3. Input: B_subtilis_168.ptt , E_coli_K12_MG1655.ptt , Halobacterium_NRC1.ptt , Synechocystis_PCC6803_uid159873.ptt , 2088090036.gff

4. Description: This Python script predicts operons in the genome of Escherichia coli K12, Bacillus Subtilis, Halobacterium, Synechocystis and Crop Microbiome by parsing the PTT (protein table) and (gff) file to extract gene information and then identifying operons ( longest contigous multi-gene transcriptional units). The code iterates through the genes in the dataset, grouping adjacent genes on the same strand into operons if they are located close to each other. The main function prints out details of each operon, including its genomic coordinates and the genes it encompasses.

5. Execution Clone the repository. Download 1.2088090036.gff 2.B_subtilis_168.ptt 3.E_coli_K12_MG1655.ptt 4.Halobacterium_NRC1.ptt 5.Synechocystis_PCC6803_uid159873.ptt. Download and Run the A-3.ipynb file. Check the output.

6. Output: Operons of all the genomes are predicted.

### Assignment-4




