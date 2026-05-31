# Genome-assembly-with-Velvet
Genome assembly with Velvet: Background
Velvet is one of a number of de novo assemblers that use short read sets as input (e.g. Illumina Reads). The assembly method is based on the manipulation of de Bruijn graphs, via the removal of errors and the simplification of repeated regions.

For this tutorial, I have a set of reads from an imaginary Staphylococcus aureus bacterium with a miniature genome (197,394 bp). Our mutant strain read set was sequenced with the whole genome shotgun method, using an Illumina DNA sequencing instrument. From these reads, I would like to rebuild our imaginary Staphylococcus aureus bacterium via a de novo assembly of a short read set using the Velvet assembler.

I also have a sequence for a reference genome that we will use later in the tutorial.

Agenda
In this tutorial, I will deal with:

Genome assembly with Velvet: Background
Get the data
Evaluate the input reads
Assemble reads with Velvet
Collect some statistics on the contigs
