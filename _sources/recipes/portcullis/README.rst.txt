:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'portcullis'
.. highlight: bash

portcullis
==========

.. conda:recipe:: portcullis/1.1.0
   :replaces_section_title:

   Splice junction analysis and filtering from BAM files

   :homepage: https://github.com/maplesond/portcullis
   :license: GPL3
   :recipe: /`portcullis <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/portcullis>`_/`1.1.0 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/portcullis/1.1.0>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/portcullis/1.1.0/meta.yaml>`_

   


.. conda:package:: portcullis

   |downloads_portcullis| |docker_portcullis|

   :versions: 1.1.1-3, 1.1.0-0
   
   :depends libgcc: 
   
   :depends numpy: 
   
   :depends pandas: 
   
   :depends python: 3.5*
   
   :depends samtools: 
   
   :depends tabulate: 
   
   :depends zlib: 1.2.11*
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install portcullis

   and update with::

      conda update portcullis

   or use the docker container::

      docker pull quay.io/biocontainers/portcullis:<tag>

   (see `portcullis/tags`_ for valid values for ``<tag>``)


.. |downloads_portcullis| image:: https://img.shields.io/conda/dn/bioconda/portcullis.svg?style=flat
   :alt:   (downloads)
.. |docker_portcullis| image:: https://quay.io/repository/biocontainers/portcullis/status
   :target: https://quay.io/repository/biocontainers/portcullis
.. _`portcullis/tags`: https://quay.io/repository/biocontainers/portcullis?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/portcullis/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/portcullis/README.html