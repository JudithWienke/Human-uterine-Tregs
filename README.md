# Human-uterine-Tregs
Dataset of raw and normalized read counts concerning publication by Wienke et al. JCI insight 2020

Whole transcriptome sequencing
For RNA isolation, the vials were thawed at room temperature and 100 µL chloroform was added to each vial. The vials were shaken well and spun down at 12000g for 15 minutes at 4⁰C. The aqueous phase was transferred into a new tube and RNA was mixed with 1ul of GlycoBlue (Invitrogen) and precipitated with 250 µL isopropanol. Cells were incubated at -20⁰C for one hour and subsequently spun down at 12000g for 10 minutes. The supernatant was carefully discarded and the RNA pellet was washed twice with 375 µL 75% ethanol. Vials were stored at -80⁰C until library preparation. Low input RNA sequencing libraries from biological sorted cell population replicates were prepared using the Cel-Seq2 Sample Preparation Protocol(136) and sequenced as 2 x 75bp paired-end  on a NextSeq 500 (Utrecht Sequencing Facility). The reads were demultiplexed and aligned to human cDNA reference using the BWA (0.7.13).(137) Multiple reads mapping to the same gene with the same unique molecular identifier (UMI, 6bp long) were counted as a single read. 

Data analysis
RNA sequencing data were normalized per million reads per sample. 
