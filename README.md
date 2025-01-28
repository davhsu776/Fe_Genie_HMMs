# Fe_Genie_HMMs

Hidden Markov Models for FeGenie (https://github.com/Arkadiy-Garber/FeGenie) used to search for _Geobacter_-like multiheme-cytochromes in Hsu _et al._ (2024). HMMs for CbcA, CbcB, CbcL, ExtA, ExtB, ExtC, and ExtD are included, along with the alignment files used to generate the HMMs. To use the HMMs, move the files into their matching location within the iron_recuction hmm folder of FeGenie (Ex. /fegenie-1.2/hmms/iron/iron_reduction/). The HMM-bitcutoffs.txt file listed was ammended from the release version of FeGenie, so the cutoffs for CbcA, CbcB, CbcL, ExtA, ExtB, ExtC, and ExtD have to be manually appended to your version of the HMM-bitcutoffs.txt file (found in hmms/iron/). They can be found in the uploaded HMM-bitcutoffs.txt file or listed below: 

CbcL	130.0  
CbcB	150.0  
CbcA	200.0  
ExtA_pcc_cyt	90.0  
ExtB_porin	100.0  
ExtC_pcc_lp_cyt	100.0  
ExtD_pcc_lp_cyt	100.0  

Citations:  
Garber AI, Nealson KH, Okamoto A, McAllister SM, Chan CS, Barco RA, and Merino N (2020) FeGenie: A Comprehensive Tool for the Identification of Iron Genes and Iron Gene Neighborhoods in Genome and Metagenome Assemblies. Front Microbiol 11:37. https://doi.org/10.3389/fmicb.2020.00037

Hsu D, Flynn JR, Schuler CJ, Santelli CM, Toner BM, Bond DR, and Gralnick JA (2024) Isolation and genomic analysis of “_Metallumcola ferriviriculae_” MK1, a Gram-positive, Fe(III)-reducing bacterium from the Soudan Underground Mine, an iron-rich Martian analog site. Appl Environ Microbiol. 90:e00044-24. https://doi.org/10.1128/aem.00044-24
