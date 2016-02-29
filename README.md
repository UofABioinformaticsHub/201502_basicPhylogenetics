# 2015-02-29 Basic Phylogenetics Tutorial  
UofA Bioinformatics Hub

## Basic command-line tutorial for phylogenetic analysis

Created by: Jimmy (jimmymbreen@gmail.com)  
System: MacOSX

### Before we start

Programs needed:
- clustal-omega (http://www.clustal.org/omega/#Download)
- MAFFT (http://mafft.cbrc.jp/alignment/software/)
- RAxML (http://sco.h-its.org/exelixis/web/software/raxml/index.html)
- git (https://git-scm.com/)
- biopython (http://biopython.org/wiki/Download)

To install clustal-omega, MAFFT, RAxML and git on MacOSX you will need to install homebrew:

```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

After that run:

```brew install mafft clustal-omega git```

For python stuff like biopython we will need to install pip:

```sudo easy_install pip```
(You'll need your admin password for this)

```pip install biopython```

Download all the data for the tutorial:

```git clone https://github.com/UofABioinformaticsHub/201502_basicPhylogenetics.git```









