:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-smite'
.. highlight: bash

bioconductor-smite
==================

.. conda:recipe:: bioconductor-smite
   :replaces_section_title:

   This package builds on the Epimods framework which facilitates finding weighted subnetworks \(\"modules\"\) on Illumina Infinium 27k arrays using the SpinGlass algorithm\, as implemented in the iGraph package. We have created a class of gene centric annotations associated with p\-values and effect sizes and scores from any researchers prior statistical results to find functional modules.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/SMITE.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-smite <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-smite>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-smite/meta.yaml>`_
   :links: biotools: :biotools:`smite`, doi: :doi:`10.1186/s12859-017-1477-3`

   


.. conda:package:: bioconductor-smite

   |downloads_bioconductor-smite| |docker_bioconductor-smite|

   :versions: 1.10.0-0, 1.8.0-0, 1.6.0-0
   
   :depends bioconductor-annotationdbi: >=1.44.0,<1.45.0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   
   :depends bioconductor-bionet: >=1.42.0,<1.43.0
   
   :depends bioconductor-genelendatabase: >=1.18.0,<1.19.0
   
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   
   :depends bioconductor-goseq: >=1.34.0,<1.35.0
   
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   
   :depends bioconductor-kegg.db: >=3.2.0,<3.3.0
   
   :depends bioconductor-org.hs.eg.db: >=3.7.0,<3.8.0
   
   :depends bioconductor-reactome.db: >=1.66.0,<1.67.0
   
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends r-ggplot2: 
   
   :depends r-hmisc: 
   
   :depends r-igraph: 
   
   :depends r-plyr: 
   
   :depends r-scales: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-smite

   and update with::

      conda update bioconductor-smite

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-smite:<tag>

   (see `bioconductor-smite/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-smite| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-smite.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-smite| image:: https://quay.io/repository/biocontainers/bioconductor-smite/status
   :target: https://quay.io/repository/biocontainers/bioconductor-smite
.. _`bioconductor-smite/tags`: https://quay.io/repository/biocontainers/bioconductor-smite?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-smite/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-smite/README.html