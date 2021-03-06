:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-illuminahumanmethylation450kprobe'
.. highlight: bash

bioconductor-illuminahumanmethylation450kprobe
==============================================

.. conda:recipe:: bioconductor-illuminahumanmethylation450kprobe
   :replaces_section_title:

   Probe sequences from Illumina \(ftp.illumina.com\) for hm450 probes

   :homepage: https://bioconductor.org/packages/3.8/data/annotation/html/IlluminaHumanMethylation450kprobe.html
   :license: LGPL
   :recipe: /`bioconductor-illuminahumanmethylation450kprobe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-illuminahumanmethylation450kprobe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-illuminahumanmethylation450kprobe/meta.yaml>`_

   


.. conda:package:: bioconductor-illuminahumanmethylation450kprobe

   |downloads_bioconductor-illuminahumanmethylation450kprobe| |docker_bioconductor-illuminahumanmethylation450kprobe|

   :versions: 2.0.6-0
   
   :depends bioconductor-annotationdbi: >=1.44.0,<1.45.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :depends wget: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-illuminahumanmethylation450kprobe

   and update with::

      conda update bioconductor-illuminahumanmethylation450kprobe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-illuminahumanmethylation450kprobe:<tag>

   (see `bioconductor-illuminahumanmethylation450kprobe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-illuminahumanmethylation450kprobe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-illuminahumanmethylation450kprobe.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-illuminahumanmethylation450kprobe| image:: https://quay.io/repository/biocontainers/bioconductor-illuminahumanmethylation450kprobe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-illuminahumanmethylation450kprobe
.. _`bioconductor-illuminahumanmethylation450kprobe/tags`: https://quay.io/repository/biocontainers/bioconductor-illuminahumanmethylation450kprobe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-illuminahumanmethylation450kprobe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-illuminahumanmethylation450kprobe/README.html