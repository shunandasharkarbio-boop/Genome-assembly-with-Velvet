## 🧩 Genome Assembly with Velvet

The sequencing reads were assembled using **Velvet**, a de novo short-read assembler that reconstructs the genome without using a reference sequence. Velvet builds a **de Bruijn graph** by breaking the sequencing reads into smaller fragments called **k-mers**.

Choosing an appropriate **k-mer size** is a critical step in the assembly process. Smaller k-mers improve graph connectivity and help assemble low-coverage regions, while larger k-mers increase assembly specificity and reduce ambiguous connections. An optimal k-mer value provides a balance between connectivity and assembly accuracy, resulting in high-quality contigs.
