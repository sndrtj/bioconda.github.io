:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-plrs'
.. highlight: bash

bioconductor-plrs
=================

.. conda:recipe:: bioconductor-plrs
   :replaces_section_title:

   The present package implements a flexible framework for modeling the relationship between DNA copy number and gene expression data using Piecewise Linear Regression Splines \(PLRS\).

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/plrs.html
   :license: GPL (>=2.0)
   :recipe: /`bioconductor-plrs <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-plrs>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-plrs/meta.yaml>`_

   


.. conda:package:: bioconductor-plrs

   |downloads_bioconductor-plrs| |docker_bioconductor-plrs|

   :versions: 1.22.0-0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   
   :depends bioconductor-biocgenerics: >=0.28.0,<0.29.0
   
   :depends bioconductor-cghbase: >=1.42.0,<1.43.0
   
   :depends bioconductor-marray: >=1.60.0,<1.61.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends r-ic.infer: 
   
   :depends r-quadprog: 
   
   :depends r-rcsdp: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-plrs

   and update with::

      conda update bioconductor-plrs

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-plrs:<tag>

   (see `bioconductor-plrs/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-plrs| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-plrs.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-plrs| image:: https://quay.io/repository/biocontainers/bioconductor-plrs/status
   :target: https://quay.io/repository/biocontainers/bioconductor-plrs
.. _`bioconductor-plrs/tags`: https://quay.io/repository/biocontainers/bioconductor-plrs?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-plrs/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-plrs/README.html