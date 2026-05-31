MultiQC generates a webpage combining reports for FastQC on both datasets. It includes these graphs and tables:

---------------------------------------
General statistics

I need to know about the data for my analysis. In particular, I need to know the read lengths as it is important in setting the maximum k-mer size for an assembly.

----------------------------------------
Sequence Quality Histograms

Dips in quality near the beginning, middle or end of the reads may determine the trimming/cleanup methods and parameters to be used, or may indicate technical problems with the sequencing process/machine run.

-----------------------------------------
Per Sequence GC Content

High GC organisms tend not to assemble well and may have an uneven read coverage distribution.

-----------------------------------------

Per Base N Content

The presence of large numbers of Ns in reads may point to a poor quality sequencing run. You will need to trim these reads to remove Ns.

----------------------------------------

k-mer content

The presence of highly recurring k-mers may point to contamination of reads with barcodes or adapter sequences.


