:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'stream_atac'
.. highlight: bash

stream_atac
===========

.. conda:recipe:: stream_atac
   :replaces_section_title:

   STREAM\-Single\-cell Trajectories Reconstruction\, Exploration And Mapping of single\-cell data. Preprocessing steps for single cell atac\-seq data.

   :homepage: https://github.com/pinellolab/STREAM_atac
   :license: Affero
   :recipe: /`stream_atac <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/stream_atac>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/stream_atac/meta.yaml>`_

   


.. conda:package:: stream_atac

   |downloads_stream_atac| |docker_stream_atac|

   :versions: 0.3.1-0, 0.3.0-0, 0.2.0-1, 0.2.0-0, 0.1.0-0
   
   :depends anndata: 
   
   :depends bioconductor-bsgenome.hsapiens.ucsc.hg19: 
   
   :depends bioconductor-chromvar: 1.4.1.*
   
   :depends libgcc-ng: >=7.3.0
   
   :depends libgfortran-ng: >=7,<8.0a0
   
   :depends libstdcxx-ng: >=7.3.0
   
   :depends perl: >=5.26.2,<5.26.3.0a0
   
   :depends python: >=3.6,<3.7.0a0
   
   :depends r-essentials: 
   
   :depends rpy2: 
   
   :depends scikit-learn: 
   
   :depends setuptools: 
   
   :depends unzip: 
   
   :depends wget: 
   
   :depends zip: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install stream_atac

   and update with::

      conda update stream_atac

   or use the docker container::

      docker pull quay.io/biocontainers/stream_atac:<tag>

   (see `stream_atac/tags`_ for valid values for ``<tag>``)


.. |downloads_stream_atac| image:: https://img.shields.io/conda/dn/bioconda/stream_atac.svg?style=flat
   :alt:   (downloads)
.. |docker_stream_atac| image:: https://quay.io/repository/biocontainers/stream_atac/status
   :target: https://quay.io/repository/biocontainers/stream_atac
.. _`stream_atac/tags`: https://quay.io/repository/biocontainers/stream_atac?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/stream_atac/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/stream_atac/README.html