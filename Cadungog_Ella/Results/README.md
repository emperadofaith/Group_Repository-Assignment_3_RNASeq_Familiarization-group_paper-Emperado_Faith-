# Ella Pearl V. Cadungog (RNA-Seq Dataset Documentation)

**Group:** 3 - Infection

## Group Paper

### Title

*Salmonella typhi Colonization Provokes Extensive Transcriptional Changes Aimed at Evading Host Mucosal Immune Defense During Early Infection of Human Intestinal Tissue*

### Citation

Nickerson KP, Senger S, Zhang Y, Lima R, Patel S, Ingano L, Flavahan WA, Kumar DKV, Fraser CM, Faherty CS, Sztein MB, Fiorentino M, Fasano A. Salmonella Typhi Colonization Provokes Extensive Transcriptional Changes Aimed at Evading Host Mucosal Immune Defense During Early Infection of Human Intestinal Tissue. EBioMedicine. 2018 May;31:92-109. doi: 10.1016/j.ebiom.2018.04.005. Epub 2018 Apr 12. PMID: 29735417; PMCID: PMC6013756.

## Assigned RNA-Seq Sample

| RNA-Seq Characteristic | Observation |
| --- | --- |
| Run accession | SRR7029708 |
| Condition | Treatment – infected tissue biopsy |
| Sequencing type | Single-end |
| Number of reads / sequences | 23,967,050 |
| Read length | 51 bp |
| GC content | 49% |

### Biological Representation of the Sample

The sample consisted of human intestinal tissue infected with *Salmonella typhi*. It was analyzed to determine changes in gene expression in the intestinal tissue during the early stage of infection.

## FastQC Results

| FastQC Analysis | Observation |
| --- | --- |
| Basic Statistics | PASS |
| Per Base Sequence Quality | PASS; High-quality;most bases have Phred scored around 38 - 40 |
| Per Tile Sequence Quality | PASS |
| Per Sequence Quality Scores | PASS |
| Per Base Sequence Content | WARNING |
| Per Sequence GC Content | WARNING |
| Per Base N Content | PASS |
| Sequence Length Distribution | PASS |
| Sequence Duplication Levels | WARNING |
| Overrepresented Sequences | WARNING |
| Adapter Content | PASS; No significant adapter contamination detected. |

### FastQC Summary

The FastQC analysis showed that the sequencing data were generally of good quality. Most bases had Phred scores of around 38–40, indicating high base-calling accuracy and a low probability of sequencing errors. The results also showed good sequence quality across tiles and reads, with no significant undetermined bases or adapter contamination. However, warnings were observed for per-base sequence content, GC content, sequence duplication, and overrepresented sequences. These results may indicate variation in nucleotide composition and the presence of highly abundant or repeated sequences, which can occur in biological samples due to highly expressed genes or PCR amplification. The sequencing reads were suitable for further RNA-seq analysis, although the warning results should be considered during downstream analysis.

## Screenshots

The following screenshots document the RNA-seq dataset and FastQC analysis:

<img width="1860" height="701" alt="Screenshot 2026-08-25 122557" src="https://github.com/user-attachments/assets/1844fb6a-e477-462a-a41b-066e4b5979b4" />

**Figure 1.** Preview of the assigned RNA-seq dataset SRR7029706 in Galaxy.

The figure shows the imported RNA-seq dataset SRR7029706, which represents the infected tissue biopsy sample assigned for analysis. The dataset is in compressed FASTQ format (fastqsanger.gz) and has a size of 729.6 MB in Galaxy. The preview also shows the four-line FASTQ structure, which includes the sequence identifier, nucleotide sequence, separator (+), and quality-score characters. This confirms that the dataset contains both the sequencing reads and their corresponding quality information.




<img width="562" height="376" alt="Screenshot 2026-08-25 123000" src="https://github.com/user-attachments/assets/eb8f20d2-3544-4979-bd86-3a6aa8792a38" />

**Figure 2.** FastQC basic statistics of the RNA-seq dataset SRR7029706.

The FastQC basic statistics show that SRR7029706 contains 20,081,963 sequences, with each read having a length of 51 bp. The dataset has a GC content of 55% and approximately 1 Gbp of total bases. No sequences were flagged as poor quality. All in all, the basic statistics indicate that the dataset contains a large number of sequencing reads with consistent read length and no reads classified as poor quality by FastQC.




<img width="977" height="718" alt="per base sequence quality" src="https://github.com/user-attachments/assets/0de94718-9fc9-4b3d-aaf8-e272cd309792" />

**Figure 3.** Per-base sequence quality of the RNA-seq dataset SRR7029706.

The FastQC result shows that the RNA-seq reads had high per-base sequence quality. The quality scores remained in the green region across all 51 base positions, with most scores above Q30. The first few bases had slightly lower quality scores of around Q34, but these were still considered high quality. In general, the result received a PASS, indicating that the bases in the sequencing reads were generally reliable for further RNA-seq analysis.




<img width="997" height="720" alt="adapter content" src="https://github.com/user-attachments/assets/3339c42b-c78f-4b93-bb8c-4d2bc452db10" />

**Figure 3.** Adapter content analysis of the RNA-seq dataset SRR7029706.

The FastQC adapter content analysis received a PASS, with adapter levels remaining close to 0% across the reads. This indicates that no significant adapter contamination was detected in the dataset. Overall, the result suggests that adapter sequences are unlikely to interfere with further RNA-seq analysis.

## Conclusion

The RNA-seq dataset SRR7029706 showed generally good sequencing quality based on the FastQC analysis. Most bases had high quality scores, and no significant adapter contamination was detected. However, some warnings and failures were observed in sequence content, GC content, sequence duplication, and overrepresented sequences. Overall, the dataset is suitable for further RNA-seq analysis, although these quality issues should be considered when interpreting the results.
