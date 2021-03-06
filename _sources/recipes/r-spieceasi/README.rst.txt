:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-spieceasi'
.. highlight: bash

r-spieceasi
===========

.. conda:recipe:: r-spieceasi
   :replaces_section_title:

   A means to explore the structure of 16S rRNA surveys using a Structural  Topic Model coupled with functional prediction. The user provides an abundance  table\, sample metadata\, and taxonomy information\, and themetagenomics infers  associations between topics and sample features\, as well as topics and predicted  functional content. Functional prediction can be accomplished via Tax4Fun \(for  Silva references\) and PICRUSt \(for GreenGeenes references\).

   :homepage: http://github.com/EESI/themetagenomics
   :license: MIT / MIT
   :recipe: /`r-spieceasi <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-spieceasi>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-spieceasi/meta.yaml>`_

   


.. conda:package:: r-spieceasi

   |downloads_r-spieceasi| |docker_r-spieceasi|

   :versions: 0.1.4-1, 0.1.4-0
   
   :depends r-base: >=3.4.1,<3.4.2.0a0
   
   :depends r-huge: 
   
   :depends r-mass: 
   
   :depends r-matrix: 
   
   :depends r-vgam: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-spieceasi

   and update with::

      conda update r-spieceasi

   or use the docker container::

      docker pull quay.io/biocontainers/r-spieceasi:<tag>

   (see `r-spieceasi/tags`_ for valid values for ``<tag>``)


.. |downloads_r-spieceasi| image:: https://img.shields.io/conda/dn/bioconda/r-spieceasi.svg?style=flat
   :alt:   (downloads)
.. |docker_r-spieceasi| image:: https://quay.io/repository/biocontainers/r-spieceasi/status
   :target: https://quay.io/repository/biocontainers/r-spieceasi
.. _`r-spieceasi/tags`: https://quay.io/repository/biocontainers/r-spieceasi?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-spieceasi/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-spieceasi/README.html