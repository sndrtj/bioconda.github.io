:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ribosomaldatabaseproject11.5mgdb'
.. highlight: bash

bioconductor-ribosomaldatabaseproject11.5mgdb
=============================================

.. conda:recipe:: bioconductor-ribosomaldatabaseproject11.5mgdb
   :replaces_section_title:

   Metagenome annotation package with for the Ribosomal Database Project 16S rRNA Database version 11.5\, Bacterial and Archeal sequences. Contains a MgDb\-class object\, defined in the metagenomeFeatures package.

   :homepage: https://bioconductor.org/packages/3.8/data/annotation/html/ribosomaldatabaseproject11.5MgDb.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ribosomaldatabaseproject11.5mgdb <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ribosomaldatabaseproject11.5mgdb>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ribosomaldatabaseproject11.5mgdb/meta.yaml>`_

   


.. conda:package:: bioconductor-ribosomaldatabaseproject11.5mgdb

   |downloads_bioconductor-ribosomaldatabaseproject11.5mgdb| |docker_bioconductor-ribosomaldatabaseproject11.5mgdb|

   :versions: 1.00.0-0
   
   :depends bioconductor-metagenomefeatures: >=2.2.0,<2.3.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ribosomaldatabaseproject11.5mgdb

   and update with::

      conda update bioconductor-ribosomaldatabaseproject11.5mgdb

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ribosomaldatabaseproject11.5mgdb:<tag>

   (see `bioconductor-ribosomaldatabaseproject11.5mgdb/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ribosomaldatabaseproject11.5mgdb| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ribosomaldatabaseproject11.5mgdb.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-ribosomaldatabaseproject11.5mgdb| image:: https://quay.io/repository/biocontainers/bioconductor-ribosomaldatabaseproject11.5mgdb/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ribosomaldatabaseproject11.5mgdb
.. _`bioconductor-ribosomaldatabaseproject11.5mgdb/tags`: https://quay.io/repository/biocontainers/bioconductor-ribosomaldatabaseproject11.5mgdb?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ribosomaldatabaseproject11.5mgdb/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ribosomaldatabaseproject11.5mgdb/README.html