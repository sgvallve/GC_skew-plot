# GC_skew-plot
Plot a GC skew to look for the origin of replication of a bacterial genome.

The GCskew.ipynb file contains a jupyter notebook that uses Biopython and Matplotlib.
The input can be a fasta file with the complete genome sequence of a bacteria. These files are available, for example, in the GenBank database (see for example the Bacteroides_thet.fta file or download it from [https://www.ncbi.nlm.nih.gov/nuccore/CP000708.1?report=fasta&log$=seqview&format=text](https://www.ncbi.nlm.nih.gov/nuccore/NC_004663.1?report=fasta&log$=seqview&format=text)). Alternatively you can download the file from the Genbank ID (for example NC_009505.1), using the Entrez module of Biopython.

The window_size and window_pass are two of the variables that can be changed. 

The results is a plot with the GC skew (in grey, where positive GC skew values has a red pattern and negative ones has a green one) and cumulative GC skew (in blue). The minimum value of the cumulative GC skew may indicate the position of the origin of replication of this genome. The maximum value may represent the terminus region.

![imatge](https://github.com/sgvallve/GC_skew-plot/assets/124814460/78809f5b-e34c-4f0c-b074-833da8778a25)
