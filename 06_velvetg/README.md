## 📄 Assembly Outputs

The Velvet assembly generates two primary output files:

### 🧬 Contigs File

The **Contigs** file contains the assembled DNA sequences (contigs). Each contig header includes useful assembly information, such as:

- **Length** – The contig length, determined by the overlap of k-mers during assembly.
- **Coverage** – The average k-mer coverage across the contig, indicating the sequencing depth and confidence of the assembled sequence.

### 📊 Stats File

The **Stats** file provides a tabular summary of each assembled contig. It includes important assembly metrics such as **contig length**, **k-mer coverage**, and other statistical measures that help evaluate the overall quality of the genome assembly.
