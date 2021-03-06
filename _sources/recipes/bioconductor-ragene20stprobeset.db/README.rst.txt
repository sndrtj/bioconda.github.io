:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ragene20stprobeset.db'
.. highlight: bash

bioconductor-ragene20stprobeset.db
==================================

.. conda:recipe:: bioconductor-ragene20stprobeset.db
   :replaces_section_title:

   Affymetrix ragene20 annotation data \(chip ragene20stprobeset\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.8/data/annotation/html/ragene20stprobeset.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ragene20stprobeset.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ragene20stprobeset.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ragene20stprobeset.db/meta.yaml>`_

   


.. conda:package:: bioconductor-ragene20stprobeset.db

   |downloads_bioconductor-ragene20stprobeset.db| |docker_bioconductor-ragene20stprobeset.db|

   :versions: 8.7.0-0
   
   :depends bioconductor-annotationdbi: >=1.44.0,<1.45.0
   
   :depends bioconductor-org.rn.eg.db: >=3.7.0,<3.8.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ragene20stprobeset.db

   and update with::

      conda update bioconductor-ragene20stprobeset.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ragene20stprobeset.db:<tag>

   (see `bioconductor-ragene20stprobeset.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ragene20stprobeset.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ragene20stprobeset.db.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-ragene20stprobeset.db| image:: https://quay.io/repository/biocontainers/bioconductor-ragene20stprobeset.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ragene20stprobeset.db
.. _`bioconductor-ragene20stprobeset.db/tags`: https://quay.io/repository/biocontainers/bioconductor-ragene20stprobeset.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ragene20stprobeset.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ragene20stprobeset.db/README.html