:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-somaticcanceralterations'
.. highlight: bash

bioconductor-somaticcanceralterations
=====================================

.. conda:recipe:: bioconductor-somaticcanceralterations
   :replaces_section_title:

   Collection of somatic cancer alteration datasets

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/SomaticCancerAlterations.html
   :license: GPL-3
   :recipe: /`bioconductor-somaticcanceralterations <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-somaticcanceralterations>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-somaticcanceralterations/meta.yaml>`_

   


.. conda:package:: bioconductor-somaticcanceralterations

   |downloads_bioconductor-somaticcanceralterations| |docker_bioconductor-somaticcanceralterations|

   :versions: 1.18.0-0
   
   :depends bioconductor-exomecopy: >=1.28.0,<1.29.0
   
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends r-stringr: 
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-somaticcanceralterations

   and update with::

      conda update bioconductor-somaticcanceralterations

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-somaticcanceralterations:<tag>

   (see `bioconductor-somaticcanceralterations/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-somaticcanceralterations| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-somaticcanceralterations.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-somaticcanceralterations| image:: https://quay.io/repository/biocontainers/bioconductor-somaticcanceralterations/status
   :target: https://quay.io/repository/biocontainers/bioconductor-somaticcanceralterations
.. _`bioconductor-somaticcanceralterations/tags`: https://quay.io/repository/biocontainers/bioconductor-somaticcanceralterations?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-somaticcanceralterations/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-somaticcanceralterations/README.html