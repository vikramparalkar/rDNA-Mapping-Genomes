# Human and Mouse genome assemblies customized for rDNA mapping, with annotation files and sample tracks

**Files accompanying <ins>'Customized genomes for human and mouse ribosomal DNA mapping.' George SS, Pimkin M, Paralkar VR. bioRxiv (2022)</ins> are deposited here.**

This repository contains publicly accessible hg38 and mm39 genomes optimized for rDNA mapping with an additional chromosome R (chrR). Also contains annotation BED files depiciting rDNA promoters, rRNA transcribed region, and intergenic spacer (IGS) regions on chrR, along with positive and negative control tracks (BWs) shown as validation in the above preprint.


The contents of the gzipped tarball files are as follows:

1. **Human_rDNA_genome_v1.0.tar.gz**: Contains *hg38* genome masked for rDNA-like regions, with reference NCBI Genbank KY962518.1 rDNA sequence modified (as described in preprint) and inserted as an additional chrR.
      * *hg38-rDNA_v1.0.fa* and *hg38-rDNA_v1.0.fa.fai* 

2. **Human_rDNA_annotation_v1.0.tar.gz**: Contains standard RefSeq annotation for hg38 with additional annotations for chrR. Snapgene file containing nucleotide sequence and annotation regions for modified reference NCBI Genbank KY962518.1 rDNA sequence. 
      * *hg38-rDNA_v1.0.bed*
      * *Human_KY962518.1_Modified_Snapgene.dna*

3. **Human_rDNA_control_tracks_v1.0.tar.gz**: Contains Human BigWigs (BWs) generated using the workflow described in the above preprint on positive (CTCF; TBP; POLR1A; UBTF) and negative (matching Input or IgG for each positive control) controls.
      * *CTCF_Human.bw* and *InputForCTCF_Human.bw*
      * *TBP_Human.bw* and *IGGForTBP_Human.bw*
      * *POLR1A_Human.bw* and *InputForPOLR1A_Human.bw*
      * *UBTF_Human.bw* and *InputForUBTF_Human.bw*
     
4. **Mouse_rDNA_genome_v1.0.tar.gz**: Contains *mm39* genome masked for rDNA-like regions, with reference NCBI Genbank BK000964.3 rDNA sequence modified (as described in preprint) and inserted as an additional chrR.
      * *mm39-rDNA_v1.0.fa* and *mm39-rDNA_v1.0.fa.fai* 

5. **Mouse_rDNA_annotation_v1.0.tar.gz**: Contains standard RefSeq annotation for mm39 with additional annotations for chrR. Snapgene file containing nucleotide sequence and annotation regions for modified reference NCBI Genbank BK000964.3 rDNA sequence. 
      * *mm39-rDNA_v1.0.bed*
      * *Mouse_BK000964.3_Modified_Snapgene.dna*

6. **Mouse_rDNA_control_tracks_v1.0.tar.gz**: Contains Mouse BigWigs (BWs) generated using the workflow described in the above preprint on positive (CTCF; TBP; POLR1A; UBTF) and negative (matching Input or IgG for each positive control) controls.
      * *CTCF_Mouse.bw* and *InputForCTCF_Mouse.bw*
      * *TBP_Mouse.bw* and *IGGForTBP_Mouse.bw*
      * *POLR1A_Mouse.bw* and *InputForPOLR1A_Mouse.bw*
      * *UBTF_Mouse.bw* and *IGGForUBTF_Mouse.bw*
