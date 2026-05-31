Assemble reads with Velvet
Now, I want to assemble our reads to find the sequence of my imaginary Staphylococcus aureus bacterium. I will perform a de novo assembly of the reads into long contiguous sequences using the Velvet short read assembler.

The first step of the assembler is to build a de Bruijn graph. For that, it will break our reads into k-mers, i.e. fragments of length k. Velvet requires the user to input a value of k (k-mer size) for the assembly process. Small k-mers will give greater connectivity, but large k-mers will give better specificity.
