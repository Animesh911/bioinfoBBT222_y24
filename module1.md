---
layout: page
title: Module 1
permalink: /module1/
---


# Module 1. Sequence alignment

Sequence alignment is a crucial process in bioinformatics, which involves arranging sequences of DNA, RNA, or proteins to identify regions of similarity. These similarities can provide insights into functional, structural, and evolutionary relationships between the sequences. Sequence alignment is broadly classified into two types: global alignment and local alignment.


- **Global Alignment:** Aligns sequences from end-to-end, useful when sequences are of similar length and overall structure.
- **Local Alignment:** Identifies regions of similarity within long sequences, useful for finding conserved motifs or domains.

## Tools and Software
1. **BLAST (Basic Local Alignment Search Tool):** Used for local alignment, it compares a query sequence against a database of sequences.
2. **Clustal Omega:** Used for multiple sequence alignment, useful for aligning more than two sequences simultaneously.
3. **MAFFT:** Another tool for multiple sequence alignment known for its accuracy and speed.
4. **Needleman-Wunsch Algorithm:** Used for global alignment.
5. **Smith-Waterman Algorithm:** Used for local alignment.

### Sample Data
- DNA or protein sequences in FASTA format.

### Software
- Install and set up BLAST, Clustal Omega, and MAFFT on your computer or access them through online platforms.

### Procedure
#### Pairwise Alignment
1. Select two sequences for alignment.
2. Use the Needleman-Wunsch algorithm for global alignment.
3. Use the Smith-Waterman algorithm for local alignment.
4. Compare the results and note differences in aligned regions.

#### Multiple Sequence Alignment (MSA)
1. Collect multiple sequences that you wish to align.
2. Use Clustal Omega to perform the alignment.
3. Alternatively, use MAFFT for comparison.
4. Analyze the alignment to identify conserved regions and motifs.

#### BLAST Search
1. Use a sequence of interest as the query.
2. Run a BLAST search against a nucleotide or protein database.
3. Analyze the BLAST results to identify similar sequences and infer functional or evolutionary relationships.

## Results and Discussion
### Pairwise Alignment
- Present the aligned sequences with annotations highlighting identical and similar regions.
- Discuss the significance of conserved regions and the implications for functional or structural similarities.

### Multiple Sequence Alignment
- Display the MSA results with highlighted conserved motifs.
- Discuss the evolutionary relationships inferred from the alignment.
- Explain any observed sequence variations and their potential biological implications.

### BLAST Results
- Summarize the top hits from the BLAST search.
- Discuss the potential functions of similar sequences identified and their evolutionary significance.

## Conclusion
Sequence alignment is an essential technique in bioinformatics for identifying similarities between biological sequences. Through this practical, students will gain hands-on experience in performing both pairwise and multiple sequence alignments, using various tools to analyze and interpret the results, and understanding the biological significance of the aligned sequences.

## References
1. Altschul, S. F., Gish, W., Miller, W., Myers, E. W., & Lipman, D. J. (1990). Basic local alignment search tool. Journal of Molecular Biology, 215(3), 403-410.
2. Larkin, M. A., Blackshields, G., Brown, N. P., Chenna, R., McGettigan, P. A., McWilliam, H., ... & Higgins, D. G. (2007). Clustal W and Clustal X version 2.0. Bioinformatics, 23(21), 2947-2948.
3. Katoh, K., & Standley, D. M. (2013). MAFFT multiple sequence alignment software version 7: improvements in performance and usability. Molecular Biology and Evolution, 30(4), 772-780.
