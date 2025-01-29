# High-Throughput-Data-Analysis

### Assignment-1
1. Programming Language and Version: Python and Python 3.11.4.

2. Dependencies: Python Libraries. NumPy, Pandas, Seaborn.

3. Input: matrix1.txt, matrix2.txt.

4. Description: This python code generates a 12x12 Pearson correlation matrix from RPKM across various cancers in a specific patient group, using "matrix1.txt" and "matrix2.txt" files using python packages such as Numpy and Pandas. It visualizes the generated matrix as a heatmap to highlight similarities between cancers using various Python Visualization Packages such as Seaborn. Finally, the code computes a Pearson correlation between both the original matrices.

5. Execution: Assignment-1 directory Download matrix1.txt, matrix2.txt. Run the Assignment_1.ipynb file. Check the output.

6. Output: Each value of the pearson correlation between two variables of the original matrices are shown in the Heatmaps.

### Assignment-2
1. Programming Language and Version: Python and Python 3.11.4.

2. Dependencies: Python Libraries. NumPy, Pandas, Seaborn, SciPy

Input: DecayTimecourse.txt

3. Description: First the python code changes the .txt original file to .csv and then the python code calculates the half lifes of the genes in three time courses and also calculates the final half-life which is the average of the half-lifes of three time courses by handling the missing values (NaN Values) and saves the result into a .csv file. After calculating the final half-life, the code will give the outputs of (half_lifes) top 10% and bottom 10% of genes and saves them into two sepearate .csv files.(The output .csv file names are mentioned in the Output section).

4. Execution: Assignment-2 directory Download DecayTimecourse.txt. Run the Assignment -2_Half_Lives.ipynb file. Check the output.

5. Output: After running the code with the Download DecayTimecourse.txt. The output files include 1. DecayTimecourse.csv ('After Converting the DecayTimecourse.txt' to .csv) 2. half_life_results.csv (After Calculating the half-life for all the three time courses and final half_life which is average of half_life of three time courses) 3. very_low_half_lives.csv ( Contains bottom 10% of genes with low half lives) 4. very_high_half_lives.csv ( Contains Top 10% of genes with high half lives). All these files are included in the repository for references.

6. Functional_Enrichment_Analysis: Using the provided link to perform the simple functional enrichment analysis. The output files (.png) of the analysis are included in the repository.

### Assignment-3
1. Programming Language and Version: Python and Python 3.11.4.

2. Dependencies: Python Libraries. Pandas.

3. Input: B_subtilis_168.ptt , E_coli_K12_MG1655.ptt , Halobacterium_NRC1.ptt , Synechocystis_PCC6803_uid159873.ptt , 2088090036.gff

4. Description: This Python script predicts operons in the genome of Escherichia coli K12, Bacillus Subtilis, Halobacterium, Synechocystis and Crop Microbiome by parsing the PTT (protein table) and (gff) file to extract gene information and then identifying operons ( longest contigous multi-gene transcriptional units). The code iterates through the genes in the dataset, grouping adjacent genes on the same strand into operons if they are located close to each other. The main function prints out details of each operon, including its genomic coordinates and the genes it encompasses.

5. Execution: Assignment -3 directory Download 1.2088090036.gff 2.B_subtilis_168.ptt 3.E_coli_K12_MG1655.ptt 4.Halobacterium_NRC1.ptt 5.Synechocystis_PCC6803_uid159873.ptt. Download and Run the A-3.ipynb file. Check the output.

6. Output: Operons of all the genomes are predicted.

### Assignment-4

1. Programming Language and Version: Python and Python 3.11.4.

2. Dependencies: Python Libraries. Pandas and Numpy

3. Input: argR-counts-matrix.txt, E_coli_K12_MG1655.400_50.

4. Description: This Python script intially, computes a frequency matrix from a given counts matrix, using this frequency matrix a Position Weight Matrix (PWM) is then constructed by comparing the observed frequencies and displays the output (both Frequency matrix and PWM). The script then employs this PWM to scan and score potential binding sites within provided upstream regulatory regions of genes. The output displays the top 30 gene IDs with the scores.

5. Execution: Assignment-4 directory Download 1. argR-counts-matrix.txt. 2.E_coli_K12_MG1655.400_50 3.Download and Run the Assignment-4.ipynb file. Check the output.

6. Output: Displays The Frequency matrix and Position Weight Matrix and Top 30 Scoring geneids along with their scores.

### Assignment-5

1. Programming Language and Version: Python and Python 3.11.4.

2. Dependencies: Python Libraries and Packages: Numpy, Matplotlib, Scipy and Networkx

3. Input: Human-PPI-2.txt, protein-list1-2.txt, protein-list2.txt.

4. Description: This Python script intially, Analyzes the human protein interaction network, calculating each protein's degree and clustering coefficient, the average clustering coefficient for the network, and determining if the network is scale-free by plotting the log log plot of degree distribution and after that, it computes shortest paths between protein pairs between the two protein files and compares path length distributions using a Wilcoxon test to infer differences in network topology.

5. Execution: Assignment-5 directory Download 1.Human-PPI-2.txt. 2.protein-list1-2.txt 3.protein-list2.txt. 4.Download and Run the A-5.ipynb file. Check the output.

6. Output: It displays node-specific degree and clustering metrics, the network's average clustering coefficient, and a log log plot of degree distribution and also Outputs the shortest path lengths for protein pairs and a Wilcoxon test comparison of path length distributions..



