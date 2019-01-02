# Data_for_DBH-Manuscript_PLoS_One
Data for PLoS One manuscript entitled

### A Single Nucleotide Polymorphism in Dopamine Beta Hydroxylase (rs6271(C>T)) is Over-represented in Inflammatory Bowel Disease Patients and Reduces Circulating Enzyme.

Eugene.Gonzalez-Lopez 1, Yuka.Kawasawa-Imamura 1, 2, Lijun.Zhang 2, 3, Xuemei.Huang 1, 4, 5, Walter.A.Koltun 6, Matthew.D. Coates *, 6§ & Kent.E.Vrana*, 1§

1.	Department of Pharmacology, Penn State College of Medicine, Hershey, PA, USA
2.	Genome Sciences Core Facility, Institute for Personalized Medicine, Pennsylvania State University College of Medicine, Hershey, PA
3.	Department of Biochemistry and Molecular Biology, Pennsylvania State University College of Medicine, Hershey, PA
4.	Department of Neurology, Pennsylvania State University College of Medicine, Milton S. Hershey Medical Center, Hershey, PA, USA
5.	Departments of Neurology, Neurosurgery and Radiology, Milton S. Hershey Medical Center, and Kinesiology, Pennsylvania State University, Hershey, PA, USA
6.	Department of Surgery, Division of Colon and Rectal Surgery, Pennsylvania State University, Hershey, PA, USA
7.	Department of Medicine, Division of Gastroenterology & Hepatology, Pennsylvania State University Hershey Medical Center, Hershey, PA, USA

§ Corresponding authors:
Email: kvrana@pennstatehealth.psu.edu (KV)
Email: mcoates@pennstatehealth.psu.edu (MC)
* These authors contributed equally to this work

## Abstract
Inflammatory bowel diseases (IBD) are associated with altered neuronal regulation of the gastrointestinal (GI) tract and release of norepinephrine (NE). As sympathetic innervation of the GI tract modulates motility, blood flow, and immune function, changes in NE signaling may alter the risk of developing IBD. Dopamine beta-hydroxylase (DβH), the enzyme responsible for NE production, has been suggested to play a critical role in IBD, however the exact mechanism is unknown. We hypothesized that genetic variants of DβH could increase the risk of IBD. We performed genetic analysis on 45 IBD patients and 74 controls. IBD patients were screened by targeted exome sequencing and compared with NeuroX DβH single nucleotide polymorphism (SNP) genotyping data of the controls. Serum DβH protein levels for 15 IBD patients and 13 controls were evaluated using immunoblots and competitive ELISA. Seven SNPs were observed from DβH targeted exome sequencing in the 45 IBD patients. A single non-synonymous SNP, rs6271 (Arg549Cys), had a significant association with IBD patients; the odds ratio was a 5.6 times higher SNP frequency in IBD patients compared to controls (p=0.002). We also examined the function and availability of the protein in both the IBD and control patients’ sera bearing DβH Arg549Cys. Both control and IBD subjects bearing the heterozygote allele had statistically lower DβH protein levels while the intrinsic enzyme activity was higher. This is the first report of a noradrenergic genetic polymorphism (rs6271; Arg549Cys) associated with IBD. This polymorphism is associated with significantly lower levels of circulating DβH.

# Data 

**Next Generation Deep Sequencing:** A custom capture oligonucleotide set was designed using the SureDesign platform from Agilent Technologies (SureSelectXT Custom Capture Oligo) against DβH.  Primers for targeted regions of the promoter (10 kb upstream region from the transcription start site) and 12 exons including 5′ and 3′ untranslated regions (UTRs) of the DβH gene locus (9q34) were used to construct a sequencing library using the KAPA LTP Library Preparation Kit (Kapa Biosystems, Inc., Wilmington, MA) combined with a SureSelectXT Reagent Kit (Agilent Technologies), and sequenced on an Illumina HiSeq 2500 sequencer (Illumina, Inc., San Diego, CA) at read length of paired-end 2x100 bp.  Generated reads were aligned to the GRCh37 human reference genome using the Burrows-Wheeler alignment. Variant detection and analysis were performed using the GATK Best Practice for germline SNP/indel finding workflow (Broad Institute). ANNOVAR software was used to annotate the variants and identify synonymous, non-synonymous and deleterious variants for further analysis. 

***File 1 Targeted Exome Data on DBH Gene for IBD patients.vcf***
Note for rigor and reproducibility one of the patient sample MC09 was duplicated as MC23 in the Deep Sequencing

**NeuroX Genotyping Data Acquisition and Analysis of Control Samples:** Single-nucleotide polymorphism (SNP) genotyping on 74 control patients population was performed on whole blood DNA samples extracted by the National Institute of Neurological Disorders and Stroke (NINDS) Parkinson's Disease Biomarkers Program (PDBP) using the Illumina NeuroX array. A total of 269,476 variants were genotyped, and the Genotyping Analysis Module within Genome Studio version 1.9.4 was used to call participant genotypes. We specifically extracted the DβH SNP data from the NINDS NeuroX genotyping data. For rigor and reproducibility, a TaqMan SNP Genotyping assays designed against the rs6271 and rs77905 SNPs (Life Technologies, Thermo Fisher Scientific, Grand Island, NY) were used to verify the DβH genotype of each patient and control. DβH genotypes that were analyzed by TaqMan matched 100% to the targeted exome sequencing results

***File 2 Taqman_And_NeuroX_DBH_Control_n74.xlsx***

## Citation Information: 
Gonzalez-Lopez E, Imamura Kawasawa Y, Zhang L,  Huang X, Koltun WA, Coates MD and  Vrana KE (2019)A Single Nucleotide Polymorphism in Dopamine Beta Hydroxylase (rs6271(C>T)) is Over-represented in Inflammatory Bowel Disease Patients and Reduces Circulating Enzyme. PLoS ONE
