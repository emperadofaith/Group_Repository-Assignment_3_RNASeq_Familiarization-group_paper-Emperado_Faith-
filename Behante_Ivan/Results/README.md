# Assignment3_RNAseq_BEHANTE_Group_3

**Title:** Salmonella Typhi Colonization Provokes Extensive Transcriptional Changes Aimed at Evading Host Mucosal Immune Defense During Early Infection of Human Intestinal Tissue

**Reference:** Nickerson KP, Senger S, Zhang Y, Lima R, Patel S, Ingano L, Flavahan WA, Kumar DKV, Fraser CM, Faherty CS, Sztein MB, Fiorentino M, Fasano A. Salmonella Typhi Colonization Provokes Extensive Transcriptional Changes Aimed at Evading Host Mucosal Immune Defense During Early Infection of Human Intestinal Tissue. EBioMedicine. 2018 May;31:92-109. doi: 10.1016/j.ebiom.2018.04.005. Epub 2018 Apr 12. PMID: 29735417; PMCID: PMC6013756.

**Assigned RNA-seq accession number:** SRR7029703

**Condition:** Uninfected tissue biopsy

**Biological Representation:** The sample SRR7029703 represents an uninfected human intestinal tissue biopsy, serving as the control condition. It provides baseline gene expression data that can be compared with Salmonella Typhi-infected tissues to identify transcriptional changes caused by early infection.

**Data type:** Single-end

**Number of Reads:** 22,642,554 bp

**Read length:** 51 bp

**GC content:** 50% 

**Galaxy History**

<img width="280" height="527" alt="image" src="https://github.com/user-attachments/assets/93fe3154-892e-4268-8667-571e91203a43" />

*Figure 1.* Galaxy history showing the imported RNA-seq dataset used to analyze the sequence.

<img width="656" height="424" alt="summary" src="https://github.com/user-attachments/assets/33cff514-ef1e-4706-9a38-918e2c692e24" />

*Figure 2.* Summary of FastQC results.

# Useful Screenshots
<img width="452" height="311" alt="basic stats" src="https://github.com/user-attachments/assets/a501189c-e00b-4f39-9ca1-84f553306501" />

*Figure 3.* Basic statistics table

<img width="1097" height="374" alt="SRR7029703" src="https://github.com/user-attachments/assets/c2483608-4974-4fba-9c5c-974a161b751b" />

*Figure 4.* Data imported to by using Faster Download and Extract in FASTQ tool

<img width="437" height="330" alt="perbase sequence" src="https://github.com/user-attachments/assets/958be74a-1f8d-426c-8c3a-21f315bd7c61" />

*Figure 5.* FASTQC per base sequence quality graph

# Interpretation question and answers

**1. What biological question was the original RNA-seq study trying to answer?**

The study investigated how *Salmonella typhi* interacts with human intestinal tissue during the early stages of infection. The researchers focused on identifying changes in gene expression that occur during colonization and understanding how these changes may help the bacteria survive while avoiding or weakening the host's mucosal immune response.

**2. Why did the authors use RNA-seq instead of only examining the genome?**

Looking at the genome can tell researchers what genes an organism possesses, but it cannot show which genes are currently active. RNA-seq was used to measure gene expression and detect changes in transcription during infection, providing information about the biological response occurring under that specific condition.

**3. What is the difference between genomic DNA and the RNA molecules measured by RNA-seq?**

Genomic DNA contains the complete genetic blueprint of an organism and generally remains the same among its cells. RNA, however, is produced from genes that are being expressed and can change depending on the cell's condition or environment. Therefore, RNA-seq provides a snapshot of which genes are active during a particular biological process, such as S. Typhi infection.

**4. What is a biological replicate and why is it important?**

A biological replicate is an independent sample collected under the same experimental condition. Replicates are important because natural biological differences can occur between samples. By comparing several independent samples, researchers can determine whether observed changes in gene expression are truly related to the treatment or infection rather than random variation.

**5. What is the difference between single-end and paired-end sequencing?**

In single-end sequencing, each DNA or RNA fragment is sequenced from only one side, producing one read per fragment. Paired-end sequencing reads both ends of the same fragment, providing two connected reads and more information about the sequence. In this study, the researchers used single-end sequencing with 50-bp reads.

**6. What is a FASTQ file?**

A FASTQ file is a common format used to store raw sequencing data. Each sequencing read contains four lines: the read identifier, the nucleotide sequence, a separator, and the corresponding quality scores. These quality scores indicate how confident the sequencing machine is in identifying each nucleotide.

**7. What information does FastQC provide?**

FastQC is used to evaluate the overall quality of sequencing reads before further analysis. It examines factors such as per-base sequence quality, GC content, sequence duplication, adapter contamination, and overrepresented sequences. The results help identify possible problems that may need to be corrected before downstream analysis.

**8. What does a high per-base quality score indicate?**

A high per-base quality score means that the sequencing instrument has a high level of confidence that a particular nucleotide was identified correctly. In general, higher scores indicate more reliable sequencing data.

**9. Why can adapter contamination be a problem?**

Adapters are artificial DNA sequences added during library preparation. If they are still present in the sequencing reads, they may be mistakenly included during analysis and can interfere with read alignment or other downstream processes. Therefore, contaminated reads may need adapter trimming before analysis.

**10. Were all RNA-seq samples in your group similar in quality? Explain.**

Overall, the samples showed generally comparable sequencing quality, particularly in terms of per-base quality and low adapter contamination. However, some differences were observed in GC content, duplication levels, sequence composition, or overrepresented sequences, which may reflect technical or biological variation among samples.

**11. Did any sample show a possible quality problem? What was it?**

Although the sequencing data were generally of good quality, some samples showed warnings related to factors such as GC distribution, sequence duplication, or overrepresented sequences. These results do not necessarily mean that the data are unusable, but they should be considered before proceeding with downstream analysis.

**12. What additional steps would be needed before the researchers could compare gene expression between control and treatment samples?**

Before comparing gene expression, the raw reads should be checked and cleaned through quality control and trimming when necessary. The processed reads can then be mapped to an appropriate reference genome or transcriptome, followed by counting or quantifying gene expression. Statistical analysis can then be performed to identify genes that are significantly different between the control and infected samples.

**Summary**

This RNA-seq study examined changes in gene activity during the early interaction between *Salmonella typhi* and human intestinal tissue. RNA-seq allowed the researchers to observe which genes were actively expressed, while FastQC helped assess the quality of the sequencing data. After quality control, processing, alignment, and quantification, the researchers could compare the control and infected samples to identify significant differences in gene expression.
