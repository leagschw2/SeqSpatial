# SeqSpatial
Sequencing Based Spatial Transcriptomics maps gene expression while preserving the spatial context of cells within a tissue.
	Materials:
    1. Tissue Slides
    2. Barcode Slide
The tissue is permeabilized so that the mRNA from cells in the tissue can diffuse out and be captured on the slide. Next, the mRNA  iS hybridized to the capture probes present in the specific spots on the slide. Each spot on the slide will capture the RNA from a small area of the tissue, linking the RNA molecules to their precise location. To amplify the signal, the mRNA is reverse transcribed into cDNA, which is further amplified. The cDNA is then subjected to high-throughput RNA sequencing, which generates millions of reads corresponding to the RNA molecules captured from each spot on the tissue. Each read includes:
  - The UMI (to track individual mRNA molecules),
  - The spatial barcode (to track the location in the tissue where the mRNA was captured),
  - The sequence of the captured mRNA (to identify the specific genes expressed).
The reads are mapped to the reference genome to identify the gene of origin (based on the mRNA sequence), the location in the tissue (based on the spatial barcode), and the abundance (based on UMI counts).

Github Usernames of group Members: marilugar
ChatGPT was used to describe the method of sequence based spatial transcriptomics. The following prompts were used:
1. What is Sequencing Based Spatial Transcriptomics
2. How does Sequencing Based Spatial Transcriptomics work?
3. Are you describing visium?
