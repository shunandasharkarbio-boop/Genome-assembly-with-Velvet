## 📈 Assembly Quality Assessment (QUAST)

The assembled genome was evaluated using **QUAST (Quality Assessment Tool for Genome Assemblies)**. QUAST compares the assembled contigs against the reference genome and generates an interactive HTML report containing detailed assembly quality metrics.

The report includes:

- **Assembly Accuracy** – Measures how well the assembly matches the reference genome, including genome fraction covered and duplication ratio.
- **Misassembly Analysis** – Identifies structural errors where contigs are incorrectly assembled, such as incorrect joins, inversions, or misplaced regions.
- **Unaligned Regions** – Reports contig regions that do not align to the reference genome.
- **Sequence Errors** – Summarizes mismatches and small insertions/deletions (indels) relative to the reference.
- **Assembly Statistics** – Provides key metrics such as the total number of contigs, largest contig size, total assembly length, N50, and other indicators used to evaluate assembly quality.
