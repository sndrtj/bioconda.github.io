:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-grndata'
.. highlight: bash

bioconductor-grndata
====================

.. conda:recipe:: bioconductor-grndata
   :replaces_section_title:

   Simulated expression data for five large Gene Regulatory Networks from different simulators

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/grndata.html
   :license: GPL-3
   :recipe: /`bioconductor-grndata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-grndata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-grndata/meta.yaml>`_

   


.. conda:package:: bioconductor-grndata

   |downloads_bioconductor-grndata| |docker_bioconductor-grndata|

   :versions: 1.14.0-0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-grndata

   and update with::

      conda update bioconductor-grndata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-grndata:<tag>

   (see `bioconductor-grndata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-grndata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-grndata.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-grndata| image:: https://quay.io/repository/biocontainers/bioconductor-grndata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-grndata
.. _`bioconductor-grndata/tags`: https://quay.io/repository/biocontainers/bioconductor-grndata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-grndata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-grndata/README.html