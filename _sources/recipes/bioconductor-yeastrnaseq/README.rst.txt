:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-yeastrnaseq'
.. highlight: bash

bioconductor-yeastrnaseq
========================

.. conda:recipe:: bioconductor-yeastrnaseq
   :replaces_section_title:

   A selection of RNA\-Seq data from a yeast transcriptome experiment.

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/yeastRNASeq.html
   :license: GPL
   :recipe: /`bioconductor-yeastrnaseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yeastrnaseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yeastrnaseq/meta.yaml>`_

   


.. conda:package:: bioconductor-yeastrnaseq

   |downloads_bioconductor-yeastrnaseq| |docker_bioconductor-yeastrnaseq|

   :versions: 0.20.0-0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-yeastrnaseq

   and update with::

      conda update bioconductor-yeastrnaseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-yeastrnaseq:<tag>

   (see `bioconductor-yeastrnaseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-yeastrnaseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-yeastrnaseq.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-yeastrnaseq| image:: https://quay.io/repository/biocontainers/bioconductor-yeastrnaseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-yeastrnaseq
.. _`bioconductor-yeastrnaseq/tags`: https://quay.io/repository/biocontainers/bioconductor-yeastrnaseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-yeastrnaseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-yeastrnaseq/README.html