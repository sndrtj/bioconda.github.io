:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chrogps'
.. highlight: bash

bioconductor-chrogps
====================

.. conda:recipe:: bioconductor-chrogps
   :replaces_section_title:

   We provide intuitive maps to visualize\, analyze and compare the association between genetic elements based on their epigenetic profiles. The approach is based on Multi\-Dimensional Scaling\, and includes a parallelized implementation for handling high dimensional datasets. We provide several sensible distance metrics\, and adjustment procedures to remove systematic biases typically observed when merging data obtained under different technologies or genetic backgrounds. We also provide functions and methods to perform differential analysis of epigenome maps at factor and gene level.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/chroGPS.html
   :license: GPL (>=2.14)
   :recipe: /`bioconductor-chrogps <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chrogps>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chrogps/meta.yaml>`_

   


.. conda:package:: bioconductor-chrogps

   |downloads_bioconductor-chrogps| |docker_bioconductor-chrogps|

   :versions: 2.0.1-0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends r-changepoint: 
   
   :depends r-cluster: 
   
   :depends r-dppackage: 
   
   :depends r-ellipse: 
   
   :depends r-icsnp: 
   
   :depends r-mass: 
   
   :depends r-vegan: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chrogps

   and update with::

      conda update bioconductor-chrogps

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chrogps:<tag>

   (see `bioconductor-chrogps/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chrogps| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chrogps.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-chrogps| image:: https://quay.io/repository/biocontainers/bioconductor-chrogps/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chrogps
.. _`bioconductor-chrogps/tags`: https://quay.io/repository/biocontainers/bioconductor-chrogps?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chrogps/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chrogps/README.html