:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-a4base'
.. highlight: bash

bioconductor-a4base
===================

.. conda:recipe:: bioconductor-a4base
   :replaces_section_title:

   Automated Affymetrix Array Analysis

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/a4Base.html
   :license: GPL-3
   :recipe: /`bioconductor-a4base <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-a4base>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-a4base/meta.yaml>`_
   :links: biotools: :biotools:`a4base`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-a4base

   |downloads_bioconductor-a4base| |docker_bioconductor-a4base|

   :versions: 1.30.0-0, 1.28.0-0, 1.26.0-0
   
   :depends bioconductor-a4core: >=1.30.0,<1.31.0
   
   :depends bioconductor-a4preproc: >=1.30.0,<1.31.0
   
   :depends bioconductor-annaffy: >=1.54.0,<1.55.0
   
   :depends bioconductor-annotationdbi: >=1.44.0,<1.45.0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   
   :depends bioconductor-genefilter: >=1.64.0,<1.65.0
   
   :depends bioconductor-limma: >=3.38.0,<3.39.0
   
   :depends bioconductor-multtest: >=2.38.0,<2.39.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends r-glmnet: 
   
   :depends r-gplots: 
   
   :depends r-mpm: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-a4base

   and update with::

      conda update bioconductor-a4base

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-a4base:<tag>

   (see `bioconductor-a4base/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-a4base| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-a4base.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-a4base| image:: https://quay.io/repository/biocontainers/bioconductor-a4base/status
   :target: https://quay.io/repository/biocontainers/bioconductor-a4base
.. _`bioconductor-a4base/tags`: https://quay.io/repository/biocontainers/bioconductor-a4base?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-a4base/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-a4base/README.html