# sspace_longread
The modified version of sspac_longread.pl, add compatibility with blasr5.x 


To use this version of sspace_longread, you need 
- perl4 supportted getopts.pl
```
# in cpan
install Perl4::CoreLibs
```


- blasr 5.2p1 (Note, the blasr 5.3 in bioconda have bug in .so link)
```
# easiest way to install blasr is conda
conda install -c bioconda blasr=5.2p1
```
