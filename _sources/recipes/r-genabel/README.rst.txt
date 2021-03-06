:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-genabel'
.. highlight: bash

r-genabel
=========

.. conda:recipe:: r-genabel
   :replaces_section_title:

   

   :homepage: 
   :license: 
   :recipe: /`r-genabel <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-genabel>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-genabel/meta.yaml>`_

   


.. conda:package:: r-genabel

   |downloads_r-genabel| |docker_r-genabel|

   :versions: 1.8_0-0
   
   :depends libgcc: 
   
   :depends r-base: 3.4.1*
   
   :depends r-genabel.data: 
   
   :depends r-mass: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-genabel

   and update with::

      conda update r-genabel

   or use the docker container::

      docker pull quay.io/biocontainers/r-genabel:<tag>

   (see `r-genabel/tags`_ for valid values for ``<tag>``)


.. |downloads_r-genabel| image:: https://img.shields.io/conda/dn/bioconda/r-genabel.svg?style=flat
   :alt:   (downloads)
.. |docker_r-genabel| image:: https://quay.io/repository/biocontainers/r-genabel/status
   :target: https://quay.io/repository/biocontainers/r-genabel
.. _`r-genabel/tags`: https://quay.io/repository/biocontainers/r-genabel?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-genabel/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-genabel/README.html