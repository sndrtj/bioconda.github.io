:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-yri1kgv'
.. highlight: bash

bioconductor-yri1kgv
====================

.. conda:recipe:: bioconductor-yri1kgv
   :replaces_section_title:

   expression \+ genotype on 79 unrelated YRI individuals

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/yri1kgv.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-yri1kgv <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yri1kgv>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yri1kgv/meta.yaml>`_

   


.. conda:package:: bioconductor-yri1kgv

   |downloads_bioconductor-yri1kgv| |docker_bioconductor-yri1kgv|

   :versions: 0.24.0-0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   
   :depends bioconductor-ggbase: >=3.44.0,<3.45.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-yri1kgv

   and update with::

      conda update bioconductor-yri1kgv

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-yri1kgv:<tag>

   (see `bioconductor-yri1kgv/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-yri1kgv| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-yri1kgv.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-yri1kgv| image:: https://quay.io/repository/biocontainers/bioconductor-yri1kgv/status
   :target: https://quay.io/repository/biocontainers/bioconductor-yri1kgv
.. _`bioconductor-yri1kgv/tags`: https://quay.io/repository/biocontainers/bioconductor-yri1kgv?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-yri1kgv/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-yri1kgv/README.html