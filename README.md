# microRNAs
microRNAs Functional Clustering

microRNAs are small non-coding molecules produced by the genome to regulate its activity. These small ribo-nucleic acids (RNA) molecules are 22-24 nucleotids long and can recognize, by base-pairing (A binds U, C binds G), complementary sequences on messengers RNAs (mRNA). The consequences of the binding of a microRNA (miR) on its complementary targets' sequences (on various mRNAs) is an inhibition of mRNAs translation into proteins, such as cellular enzymes.
    
Accordingly to the [mirbase database](ftp://mirbase.org/pub/mirbase/CURRENT/README), 35,828 microRNAs from 223 species were sequenced. For exemple, the human genome encodes 2,588 miRs and the mouse genome 1,915 miRs. Here I will use the most up-to-date [TargetScan](http://www.targetscan.org/cgi-bin/targetscan/data_download.cgi?db=vert_70) database which has recently improved its target scoring algorithm to include up to 14 distinctive features [Agarwal et al. 2015](http://elifesciences.org/content/4/e05005).

Despite the progresses made for the prediction of microRNA targets, the functions of the microRNAs are still poorly understood. While most studies address the biological function of individual microRNAs, it is anticipated from the highly connected network of miRs-mRNAs interactions that microRNAs cooperate for the regulation of the cell's transcriptome (the ensemble of expressed mRNAs). 

**Could we define some functional clusters of microRNAs accordingly to their common targets?**

Read the [notebook]("microRNA_network_analysis_with_neo4j_v2.ipynb") describing one clustering solution with the Affinity Propagation algorithm.