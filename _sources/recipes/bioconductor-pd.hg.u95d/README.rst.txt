:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pd.hg.u95d'
.. highlight: bash

bioconductor-pd.hg.u95d
=======================

.. conda:recipe:: bioconductor-pd.hg.u95d
   :replaces_section_title:

   Platform Design Info for The Manufacturer\'s Name HG U95D

   :homepage: https://bioconductor.org/packages/3.8/data/annotation/html/pd.hg.u95d.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-pd.hg.u95d <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.hg.u95d>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.hg.u95d/meta.yaml>`_

   


.. conda:package:: bioconductor-pd.hg.u95d

   |downloads_bioconductor-pd.hg.u95d| |docker_bioconductor-pd.hg.u95d|

   :versions: 3.12.0-0
   
   :depends bioconductor-biostrings: >=2.50.0,<2.51.0
   
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   
   :depends bioconductor-oligo: >=1.46.0,<1.47.0
   
   :depends bioconductor-oligoclasses: >=1.44.0,<1.45.0
   
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends r-dbi: >=0.3.1
   
   :depends r-rsqlite: >=1.0.0
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pd.hg.u95d

   and update with::

      conda update bioconductor-pd.hg.u95d

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pd.hg.u95d:<tag>

   (see `bioconductor-pd.hg.u95d/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pd.hg.u95d| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pd.hg.u95d.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-pd.hg.u95d| image:: https://quay.io/repository/biocontainers/bioconductor-pd.hg.u95d/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pd.hg.u95d
.. _`bioconductor-pd.hg.u95d/tags`: https://quay.io/repository/biocontainers/bioconductor-pd.hg.u95d?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pd.hg.u95d/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pd.hg.u95d/README.html