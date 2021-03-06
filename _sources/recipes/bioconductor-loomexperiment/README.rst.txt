:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-loomexperiment'
.. highlight: bash

bioconductor-loomexperiment
===========================

.. conda:recipe:: bioconductor-loomexperiment
   :replaces_section_title:

   The LoomExperiment class provide a means to easily convert Bioconductor\'s \"Experiment\" classes to loom files and vice versa.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/LoomExperiment.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-loomexperiment <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-loomexperiment>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-loomexperiment/meta.yaml>`_

   


.. conda:package:: bioconductor-loomexperiment

   |downloads_bioconductor-loomexperiment| |docker_bioconductor-loomexperiment|

   :versions: 1.0.1-0
   
   :depends bioconductor-delayedarray: >=0.8.0,<0.9.0
   
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   
   :depends bioconductor-hdf5array: >=1.10.0,<1.11.0
   
   :depends bioconductor-rhdf5: >=2.26.0,<2.27.0
   
   :depends bioconductor-rtracklayer: >=1.42.0,<1.43.0
   
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   
   :depends bioconductor-singlecellexperiment: >=1.4.0,<1.5.0
   
   :depends bioconductor-summarizedexperiment: >=1.12.0,<1.13.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-loomexperiment

   and update with::

      conda update bioconductor-loomexperiment

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-loomexperiment:<tag>

   (see `bioconductor-loomexperiment/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-loomexperiment| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-loomexperiment.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-loomexperiment| image:: https://quay.io/repository/biocontainers/bioconductor-loomexperiment/status
   :target: https://quay.io/repository/biocontainers/bioconductor-loomexperiment
.. _`bioconductor-loomexperiment/tags`: https://quay.io/repository/biocontainers/bioconductor-loomexperiment?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-loomexperiment/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-loomexperiment/README.html