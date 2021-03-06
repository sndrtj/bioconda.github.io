:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-geneoverlap'
.. highlight: bash

bioconductor-geneoverlap
========================

.. conda:recipe:: bioconductor-geneoverlap
   :replaces_section_title:

   Test two sets of gene lists and visualize the results.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/GeneOverlap.html
   :license: GPL-3
   :recipe: /`bioconductor-geneoverlap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-geneoverlap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-geneoverlap/meta.yaml>`_
   :links: biotools: :biotools:`geneoverlap`, doi: :doi:`10.1167/iovs.16-20618`

   


.. conda:package:: bioconductor-geneoverlap

   |downloads_bioconductor-geneoverlap| |docker_bioconductor-geneoverlap|

   :versions: 1.18.0-0, 1.16.0-0, 1.14.0-0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends r-gplots: 
   
   :depends r-rcolorbrewer: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-geneoverlap

   and update with::

      conda update bioconductor-geneoverlap

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-geneoverlap:<tag>

   (see `bioconductor-geneoverlap/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-geneoverlap| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-geneoverlap.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-geneoverlap| image:: https://quay.io/repository/biocontainers/bioconductor-geneoverlap/status
   :target: https://quay.io/repository/biocontainers/bioconductor-geneoverlap
.. _`bioconductor-geneoverlap/tags`: https://quay.io/repository/biocontainers/bioconductor-geneoverlap?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-geneoverlap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-geneoverlap/README.html