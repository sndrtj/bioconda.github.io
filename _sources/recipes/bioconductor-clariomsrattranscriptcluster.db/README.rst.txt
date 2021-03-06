:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-clariomsrattranscriptcluster.db'
.. highlight: bash

bioconductor-clariomsrattranscriptcluster.db
============================================

.. conda:recipe:: bioconductor-clariomsrattranscriptcluster.db
   :replaces_section_title:

   Affymetrix clariomsrat annotation data \(chip clariomsrattranscriptcluster\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.8/data/annotation/html/clariomsrattranscriptcluster.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-clariomsrattranscriptcluster.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomsrattranscriptcluster.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomsrattranscriptcluster.db/meta.yaml>`_

   


.. conda:package:: bioconductor-clariomsrattranscriptcluster.db

   |downloads_bioconductor-clariomsrattranscriptcluster.db| |docker_bioconductor-clariomsrattranscriptcluster.db|

   :versions: 8.7.0-0
   
   :depends bioconductor-annotationdbi: >=1.44.0,<1.45.0
   
   :depends bioconductor-org.rn.eg.db: >=3.7.0,<3.8.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-clariomsrattranscriptcluster.db

   and update with::

      conda update bioconductor-clariomsrattranscriptcluster.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-clariomsrattranscriptcluster.db:<tag>

   (see `bioconductor-clariomsrattranscriptcluster.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-clariomsrattranscriptcluster.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-clariomsrattranscriptcluster.db.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-clariomsrattranscriptcluster.db| image:: https://quay.io/repository/biocontainers/bioconductor-clariomsrattranscriptcluster.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-clariomsrattranscriptcluster.db
.. _`bioconductor-clariomsrattranscriptcluster.db/tags`: https://quay.io/repository/biocontainers/bioconductor-clariomsrattranscriptcluster.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-clariomsrattranscriptcluster.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-clariomsrattranscriptcluster.db/README.html