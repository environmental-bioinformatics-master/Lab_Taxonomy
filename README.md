# Lab for taxonomic annotation using different databases and tools

We talked about how profoundly our choice of database (or lack of reference sequences) can impact our ability to interpret our community sequencing datasets. Now, you all are going to see for yourself how significant this impact can be!

We will test the following tools:
- `mmseqs` 
- `Kraken`
- `sourmash`
- `EUKulele`

And the following databases:
- NCBI `nr` database
- NCBI `RefSeq` database
- Marine Microbial Eukaryote Transcriptome Sequencing Project (MMETSP) database with MarRef bacterial sequences
- Marine Microbial Eukaryote Transcriptome Sequencing Project (MMETSP) databas
e with MarRef bacterial sequences and _Phaeocystis_ colonial transcriptomes
- Marine Microbial Eukaryote Transcriptome Sequencing Project (MMETSP) databas
e with MarRef bacterial sequences and _Phaeocystis_ free-living transcriptomes
- Marine Microbial Eukaryote Transcriptome Sequencing Project (MMETSP) databas
e with MarRef bacterial sequences and all available _Phaeocystis_ transcriptomes

TODO for Arianna:
- download kraken RefSeq database
- download mmseqs2 uniprot databases
- download some kind of database for sourmash
- for class, all of the above should probably be the default. can do something different for the paper
- subsample from fasta file for assembly of interest using seqtk sample https://github.com/lh3/seqtk
- use reads-for-assembly to generate raw reads to profile taxonomically with Kraken https://github.com/merenlab/reads-for-assembly
