:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-biomvcclass'
.. highlight: bash

bioconductor-biomvcclass
========================

.. conda:recipe:: bioconductor-biomvcclass
   :replaces_section_title:

   Creates classes used in model\-view\-controller \(MVC\) design

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/BioMVCClass.html
   :license: LGPL
   :recipe: /`bioconductor-biomvcclass <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-biomvcclass>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-biomvcclass/meta.yaml>`_
   :links: biotools: :biotools:`biomvcclass`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-biomvcclass

   |downloads_bioconductor-biomvcclass| |docker_bioconductor-biomvcclass|

   :versions: 1.50.0-0, 1.48.0-0, 1.46.0-0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   
   :depends bioconductor-graph: >=1.60.0,<1.61.0
   
   :depends bioconductor-mvcclass: >=1.56.0,<1.57.0
   
   :depends bioconductor-rgraphviz: >=2.26.0,<2.27.0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-biomvcclass

   and update with::

      conda update bioconductor-biomvcclass

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-biomvcclass:<tag>

   (see `bioconductor-biomvcclass/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-biomvcclass| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-biomvcclass.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-biomvcclass| image:: https://quay.io/repository/biocontainers/bioconductor-biomvcclass/status
   :target: https://quay.io/repository/biocontainers/bioconductor-biomvcclass
.. _`bioconductor-biomvcclass/tags`: https://quay.io/repository/biocontainers/bioconductor-biomvcclass?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-biomvcclass/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-biomvcclass/README.html