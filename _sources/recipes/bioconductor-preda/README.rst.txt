:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-preda'
.. highlight: bash

bioconductor-preda
==================

.. conda:recipe:: bioconductor-preda
   :replaces_section_title:

   Package for the position related analysis of quantitative functional genomics data.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/PREDA.html
   :license: GPL-2
   :recipe: /`bioconductor-preda <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-preda>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-preda/meta.yaml>`_
   :links: biotools: :biotools:`preda`, doi: :doi:`10.1093/bioinformatics/btr404`

   


.. conda:package:: bioconductor-preda

   |downloads_bioconductor-preda| |docker_bioconductor-preda|

   :versions: 1.28.0-0, 1.26.1-0, 1.24.0-0
   
   :depends bioconductor-annotate: >=1.60.0,<1.61.0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   
   :depends bioconductor-multtest: >=2.38.0,<2.39.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends r-lokern: >=1.0.9
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-preda

   and update with::

      conda update bioconductor-preda

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-preda:<tag>

   (see `bioconductor-preda/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-preda| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-preda.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-preda| image:: https://quay.io/repository/biocontainers/bioconductor-preda/status
   :target: https://quay.io/repository/biocontainers/bioconductor-preda
.. _`bioconductor-preda/tags`: https://quay.io/repository/biocontainers/bioconductor-preda?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-preda/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-preda/README.html