# Shotgun metagenomic analysis
This portion of the workshop will cover a few of the basic computational approaches to studying WGS metagenomic data. 
In contrast to 16S rRNA studies (which have platforms like QIIME), there is no agreed-upon "all-in-one" analysis platform for WGS metagenomic analysis.
There are a few pretty comprehensive platforms such as:
1. [MEGAN](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/algorithms-in-bioinformatics/software/megan6/) 
a 16S and WGS platform, designed for GUI use (i.e. hard to work with on a cluster/server)
2. [Anvi'o](https://merenlab.org/software/anvio/) a WGS platform, designed for use on a server. A robust, capable platform, but with a somewhat steep learning curve and a number 
of the analyses are either non-standard or not state-of-the-art.

As such, we will be covering some of the current state-of-the-art (according to the recent [CAMI2 manuscript](https://www.biorxiv.org/content/10.1101/2021.07.12.451567v1)) stand-alone tools.

# Taxonomic profiling
In the [Taxonomic Profiling](TaxonomicProfiling.md) section, we will be covering a couple of tools capable of answering the question:
"Which taxa are present in my metagenome, and at what relative abundance?

# Assembly
In the [Assembly](Assembly.md) section, we will cover a couple tools that will take as input your short sequences and assemble them into contigs and/or scaffolds. 

# Binning
In the [Binning](Binning.md) section, we will cover tools that either:
1. Cluster the assembled contigs into putative single genome origin bins (genome binning)
2. Cluster the assembled contigs into bins which correspond to different taxa (taxonomic binning)
