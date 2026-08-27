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


<img width="1760" height="1026" alt="image" src="https://github.com/user-attachments/assets/d859e2d9-cd41-4259-ae83-99fe63fb82bb" />

**Figure 1.** Galaxy preview of the SRR7029708 RNA-seq sequencing data.

The first figure presents the SRR7029708 RNA-seq dataset after it was uploaded to Galaxy. The file is stored as a compressed FASTQ file (fastqsanger.gz) with a size of about 907 MB. The preview contains the basic FASTQ format, including the read name, nucleotide sequence, plus sign, and quality-score information. These components show that the file contains both the RNA sequencing reads and their base-quality data, which are needed for checking the quality of the biological sample.


<img width="887" height="537" alt="image" src="https://github.com/user-attachments/assets/890bde36-1d3f-4d2b-866a-cfa0710fc59f" />

**Figure 2.** Summary of the FastQC quality statistics for SRR7029708.

The second figure summarizes the main features of the sequencing data. A total of 23,967,050 reads were generated, and each read is 51 bp long. The data contain approximately 1.2 Gbp of sequence bases, with an overall GC content of 49%. No sequences were identified as poor quality. The consistent read length and large number of reads indicate that the dataset provides sufficient sequencing information for studying RNA transcripts and gene expression.


<img width="1017" height="712" alt="image" src="https://github.com/user-attachments/assets/cb169295-c7a2-4b0d-b96d-e65efdeca2bc" />

**Figure 3.** Base-by-base quality assessment of the SRR7029708 sequencing reads.

The third figure displays the quality of each nucleotide position within the sequencing reads. Most positions have Phred scores between 38 and 40, showing that the bases were identified with high accuracy. A small decrease in quality can be seen at the beginning of the reads, but the scores remain within the high-quality range. The result indicates that the sequencing reads have reliable base-call quality, which is important for accurate downstream RNA-seq analysis.


<img width="1011" height="715" alt="image" src="https://github.com/user-attachments/assets/10c7e908-8ec6-4976-8808-89b45933278b" />

**Figure 4.** Detection of adapter sequences in the SRR7029708 RNA-seq reads.

The fourth figure presents the amount of adapter sequence detected in the reads. The adapter level stays very low and remains close to 0% throughout the read positions. This means that the sequencing data contain little to no unwanted adapter sequence. The adapter contamination is unlikely to affect the identification and analysis of RNA transcripts.



**Conclusion**

The FastQC results indicate that SRR7029708 is generally a high-quality RNA-seq dataset. It contains a large number of uniform 51-bp reads, with high nucleotide quality and a GC content of 49%. The absence of significant adapter contamination also supports the reliability of the sequencing data. Although other FastQC results may show some warnings related to RNA-seq sequence composition or read duplication, the main quality results indicate that the dataset is appropriate for downstream transcriptomic and gene expression analysis.
