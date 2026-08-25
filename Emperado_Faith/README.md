# Assignment3_RNASeq_EMPERADO_Group_3

**Title:** _Salmonella_ Typhi Colonization Provokes Extensive Transcriptional Changes Aimed at Evading Host Mucosal Immune Defense During Early Infection of Human Intestinal Tissue

**Reference:** Nickerson KP, Senger S, Zhang Y, Lima R, Patel S, Ingano L, Flavahan WA, Kumar DKV, Fraser CM, Faherty CS, Sztein MB, Fiorentino M, Fasano A. Salmonella Typhi Colonization Provokes Extensive Transcriptional Changes Aimed at Evading Host Mucosal Immune Defense During Early Infection of Human Intestinal Tissue. EBioMedicine. 2018 May;31:92-109. doi: 10.1016/j.ebiom.2018.04.005. Epub 2018 Apr 12. PMID: 29735417; PMCID: PMC6013756.

**Assigned RNA-seq accession number:** SRR7029705

**Condition:** Infected tissue biopsy

**Short biological explanation:** An RNA-Seq transcriptomic profile from an infected human ileal tissue biopsy exposed to _Salmonella enterica serovar_ Typhi (S. Typhi) is biologically represented by Sample 5 (SRR7029705). This sample, which was obtained as part of research on host-pathogen interactions in the human small intestine, shows the active human gene expression response to a Salmonella Typhi bacterial infection in comparison to a baseline control of uninfected mucosa.

**Data type:** single-end

**Number of reads:** 23,750,360 bp
 
**Read length:** 51 bp

**GC content:** 50%

**Galaxy History**

<img width="386" height="647" alt="image" src="https://github.com/user-attachments/assets/6d27bd51-20eb-4921-a6c0-402387d2d49b" />

**Figure 1:** Galaxy history showing the imported RNA-seq dataset and tools used to analyze the sequence.

**FASTQC Summary**

<img width="364" height="531" alt="image" src="https://github.com/user-attachments/assets/5aaadc3e-d23f-492e-934d-23d89a130c39" />

**Figure 2:** FastQC quality control summary for sample SRR7029705. Per base sequence contents, sequence duplication levels, and overrepresented sequence show warning sign, indicating that the results deviate slightly from ideal Illumina sequencing expectations, but it does not necessarily mean the data is unusable or bad. Whereas per sequence GC content shows a fail sign, meaning the results are very different from what is normally expected for standard genomic DNA.

**FASTQ Preview**

<img width="1547" height="385" alt="image" src="https://github.com/user-attachments/assets/ec45842f-d9bd-4e4a-b6d5-8e1f46be7929" />

**Figure 3:** Each sequence read in a raw FASTQ file is stored in four lines. The first line gives information about the sequencing instrument and where the read was detected. The second line contains the 51-base DNA sequence, with N indicating a base that could not be identified. The third line is a separator (+), while the fourth line contains Phred quality scores that show how reliable each base is. Lower scores mean lower confidence, while higher scores mean the base was read more accurately.

**Per-base sequence quality**

<img width="830" height="617" alt="image" src="https://github.com/user-attachments/assets/9bbfe848-ea72-4d2e-b23f-b75ee947dfcc" />
 
 **Figure 4:** Phred quality scores across all 51 bp position bins maintained high quality (Pass), remaining well within the green acceptable zone (Q28). Mean quality scores peaked above Q38 across positions 7–23, with minor quality variation observed in the initial 5 bases (Q32–Q35), demonstrating reliable base call precision across the entirety of the reads.

 **Per sequence GC content**

 <img width="818" height="600" alt="image" src="https://github.com/user-attachments/assets/63b6ed6f-f5f0-4081-9c84-2be89bdd37a2" />

**Figure 5:** The observed GC distribution differs significantly from the expected distribution for genomic DNA. The reads show multiple peaks, indicating an uneven GC composition.

 **Interpretation question and answers**

1. What biological question was the original RNA-seq study trying to answer?

- The study aimed to determine how _Salmonella_ typhi alters gene expression during its
early interaction with human intestinal tissue. Specifically, the researchers wanted to understand how the pathogen responds to the intestinal environments and how it may modify the host's mucosal immune defenses. The study therefore examined
transcriptional changes associated with S. typhi colonization of human intestinal cells

2. Why did the authors use RNA-seq instead of only examining the genome?

- The genome shows which genes are present, but not which genes are active. RNA-seq allowed the researchers to identify genes that were being expressed or changing during S.
typhi infection.

3. What is the difference between genomic DNA and the RNA molecules measured by
RNA-seq?

- Genomic DNA represents the organism's relatively stable genetic information and
contains the complete set of genes. RNA molecules, in contrast, are produced when particular genes are expressed. Therefore, RNA provides information about which genes are actively being transcribed under specific biological conditions. In this study, RNA-seq was useful because the researchers were interested in changes in gene expression during S. typhı colonization of human intestinal tissue. The RNA data could therefore reveal changes in transcription that would not be apparent from examining the genome alone.

4. What is a biological replicate and why is it important?

- A biological replicate is a separate biological sample representing the same experimental condition. In the study, the researchers used multiple human intestinal biopsies for both the uninfected control and infected conditions, along with bacterial control samples.
Biological replicates are important because they allow researchers to determine whether an observed transcriptional difference is consistently associated with the experimental condition rather than being caused by natural variation between individual samples.
Having multiple biological replicates also strengthens the reliability of comparisons between control and infected conditions.

5. What is the difference between single-end and paired-end sequencing?

- Single-end sequencing reads each RNA-seq fragment from only one end, producing one sequence read for each fragment. Paired-end sequencing reads the same fragment from both ends. producing two related reads that provide additional information about the 13 fragment. In this study, the researchers used single-end 50-bp sequencing on an Illumina HiSeq 2500.

6. What is a FASTQ file?

- A FASTO file is a sequencing-data format that contains both the nucleotide sequences generated during sequencing and the quality information associated with those sequences. Each read is represented by four lines: a sequence identifier, the nucleotide sequence, a separator line, and quality-score. The quality scores are particularly important because they indicate the confidence of the sequencing instrument in each base call. This makes FAST different from formats such as FASTA, which primarily provide sequence information and identifiers.

7. What information does FastQC provide

- FastQC checks the quality of sequencing data. It provides information about base quality, GC content, adapter contamination, sequence duplication, and overrepresented sequences and marks results as pass, warning, or fail.

8. What does a high per-base quality score indicate?

- A high quality score means the sequencing instrument is highly confident that the reported nucleotide is correct. It generally indicates reliable sequencing reads.

9. Why can adapter contamination be a problem?

- Adapter sequences are artificial sequences added during library preparation to allow
RNA fragments to be processed and sequenced. If adapter sequences remain in the final reads, they can interfere with downstream sequence analysis because they are not part of the biological RNA being studied.

10. Were all RNA-seq samples in your group similar in quality? Explain.

- The samples were generally similar because they had good base quality and little adapter contamination. However, some samples had differences in GC content, duplication, sequence content, or overrepresented sequences.

11. Did any sample show a possible quality problem? What was it?

- The samples were generally similar because they had good base quality and little adapter contamination. However, some samples had differences in GC content, duplication, sequence content, or overrepresented sequences.

 12. What additional steps would be needed before the researchers could compare gene expression between control and treatment samples?

- The reads should first undergo quality control and trimming of adapters or low-quality bases when needed. They then need to be aligned to a reference genome or transcriptome and quantified. Finally, statistical analysis using the biological replicates can identify genes with significant differences in expression between the control and infected samples.

**Summary**

The RNA-seq study helped researchers understand how _Salmonella_ Typhi responds to and affects human intestinal tissue by showing which genes become active during infection. The quality of the sequencing data was checked using FASTQ and FastQC to make sure the results were reliable. Using biological replicates make the results more reliable by showing whether gene-expression differences are consistent across samples. Before comparing gene expression, the reads must undergo quality control, trimming, alignment, quantification, and statistical analysis.
