# readstools

#tools to manipulate multi fasta files from Illumina reads 


From a samsoft file, extract the reads that map to the reference:

perl samsoft2fasta_sihits.pl [samsoft file] > hits_file.fasta

From a samsoft file, extract the reads that do not map to the reference: 

perl samsoft2fasta_nohits.pl [samsoft file] > no_hits_file.fasta
