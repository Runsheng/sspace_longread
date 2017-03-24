# sspace_longread
A modified version of sspac_longread.pl, add compatibility with blasr5.x 


To use this version of sspace_longread, you need 
- perl4 supportted getopts.pl
```
# in cpan
install Perl4::CoreLibs
```

- blasr 5.2p1 (Note, the blasr 5.3 in bioconda have bug in .so link)
```sh
# easiest way to install blasr is conda
conda install -c bioconda blasr=5.2p1

# then create a soft link of the blasr to the same folder as the Sspace-Longread.pl
```

#### This script is just a modification from the origrin file for personal use. Please refer to the following copyright cliams in
[https://www.baseclear.com/genomics/bioinformatics/basetools/SSPACE-longread]
---------------
```
SSPACE-LONGREAD 

SSPACE-LongRead is a stand-alone program for scaffolding pre-assembled contigs using long reads (e.g. PacBio RS reads). Using the long read information, contigs (or scaffolds) are placed in the right order and orientation in so-called super-scaffolds. The SSPACE-LongRead hybrid assembly approach has been tested on a number of bacterial genomes and in most cases results in less than 10 super-scaffolds (numbers based on draft assemblies constructed with one Illumina MiSeq paired-end and one PacBio RS C2 SMRT library, both at 100X coverage).

The manuscript has been accepted for publication in BMC Bioinformatics. For citations refer to:

Boetzer M, Pirovano W: SSPACE-LongRead: scaffolding bacterial draft genomes using long read sequence information. BMC Bioinformatics 2014.

In principal the basic version of SSPACE-LongRead is free for academics, upgrades are available against a small additional fee. Commercial users need in any case to pay for a license, the exact fee depends on the size of the institution (number of employees) and the type of usage (R&D or commercial services). For more information about licenses and premium packages please contact us at info@baseclear.com.
```
