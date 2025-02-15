# Barcode Database builder
Here we develop scripts to implement in a snakemake workflow. The idea is to fetch appropriate sequences from the international sequence databases to build a reference database of DNA barcode sequences.

The repository is built on the back of jupyter notebooks on a similar topic written by Amir Szitenberg
ie this is forked from HullUni-bioinformatics/Your-Species-In-GenBank

These three Jupyter notebooks will check the representation of a list of species in GenBank, for a given gene (currently cox1) and will plot the results as stacked bars, for a given taxonomic level.  
Use *Count cox1 occurance in GenBank for a list of species* to search GenBank given a list of species.  
Use *ReadTaxonomy* to parse hierarchical taxonomy of your species  
Use *Plot* to plot the stacked barplots and histograms.  
<p xmlns:dct="http://purl.org/dc/terms/">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <span resource="[_:publisher]" rel="dct:publisher">
    <span property="dct:title">we</span></span>
  have waived all copyright and related or neighboring rights to
  this work.
</p>
