:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bsseqdata'
.. highlight: bash

bioconductor-bsseqdata
======================

.. conda:recipe:: bioconductor-bsseqdata
   :replaces_section_title:

   Example whole genome bisulfite data for the bsseq package

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/bsseqData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-bsseqdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bsseqdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bsseqdata/meta.yaml>`_

   


.. conda:package:: bioconductor-bsseqdata

   |downloads_bioconductor-bsseqdata| |docker_bioconductor-bsseqdata|

   :versions: 0.20.0-0
   
   :depends bioconductor-bsseq: >=1.18.0,<1.19.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bsseqdata

   and update with::

      conda update bioconductor-bsseqdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bsseqdata:<tag>

   (see `bioconductor-bsseqdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bsseqdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bsseqdata.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-bsseqdata| image:: https://quay.io/repository/biocontainers/bioconductor-bsseqdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bsseqdata
.. _`bioconductor-bsseqdata/tags`: https://quay.io/repository/biocontainers/bioconductor-bsseqdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bsseqdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bsseqdata/README.html