.. _`bioconductor-snplocs.hsapiens.dbsnp141.grch38`:

bioconductor-snplocs.hsapiens.dbsnp141.grch38
=============================================

|downloads|

SNP locations and alleles for Homo sapiens extracted from NCBI dbSNP Build 141. The source data files used for this package were created by NCBI on May 1st\, 2014\, and contain SNPs mapped to reference genome GRCh38. Note that these SNPs can be \"injected\" in BSgenome.Hsapiens.NCBI.GRCh38 or in BSgenome.Hsapiens.UCSC.hg38. IMPORTANT NOTE\: This package is deprecated. Please use a SNPlocs data package based on a more recent dbSNP BUILD instead \(e.g. BUILD 144 or BUILD 149\). You can call BSgenome\:\:available.SNPs\(\) from R to get the list of available SNPlocs data packages.

============= ===========
Home          https://bioconductor.org/packages/3.8/data/annotation/html/SNPlocs.Hsapiens.dbSNP141.GRCh38.html
Versions      
License       Artistic-2.0
Recipe        https://github.com/bioconda/bioconda-recipes/tree/master/recipes//bioconductor-snplocs.hsapiens.dbsnp141.grch38/meta.yaml



============= ===========



Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

   conda install bioconductor-snplocs.hsapiens.dbsnp141.grch38

and update with::

   conda update bioconductor-snplocs.hsapiens.dbsnp141.grch38



|docker|

A Docker container is available at https://quay.io/repository/biocontainers/bioconductor-snplocs.hsapiens.dbsnp141.grch38.

Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/bioconductor-snplocs.hsapiens.dbsnp141.grch38/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/bioconductor-snplocs.hsapiens.dbsnp141.grch38/README.html
.. |downloads| image:: https://anaconda.org/bioconda/bioconductor-snplocs.hsapiens.dbsnp141.grch38/badges/downloads.svg
               :target: https://anaconda.org/bioconda/bioconductor-snplocs.hsapiens.dbsnp141.grch38
.. |docker| image:: https://quay.io/repository/biocontainers/bioconductor-snplocs.hsapiens.dbsnp141.grch38/status
                :target: https://quay.io/repository/biocontainers/bioconductor-snplocs.hsapiens.dbsnp141.grch38
