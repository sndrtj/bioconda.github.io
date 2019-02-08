.. title:: Package Recipe 'spydrpick'
.. highlight: bash


spydrpick
=========

.. conda:recipe:: spydrpick
   :replaces_section_title:

   Mutual information based detection of pairs of genomic loci co\-evolving under a shared selective pressure

   :homepage: https://github.com/santeripuranen/SpydrPick
   :license: GNU Affero General Public License
   :recipe: /`spydrpick <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/spydrpick>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/spydrpick/meta.yaml>`_
   :links: doi: :doi:`10.1101/523407`

   


.. conda:package:: spydrpick

   |downloads_spydrpick| |docker_spydrpick|

   :versions: 1.0.0

   :depends: :conda:package:`libgcc-ng` >=7.3.0 :conda:package:`libstdcxx-ng` >=7.3.0 :conda:package:`pthread-stubs`  :conda:package:`tbb` >=2019.3 

   :required~by: |required_by_spydrpick|

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install spydrpick

   and update with::

      conda update spydrpick

   or use the docker container::

      docker pull quay.io/repository/biocontainers/spydrpick


.. |required_by_spydrpick| conda:required_by:: spydrpick
.. |downloads_spydrpick| image:: https://img.shields.io/conda/dn/bioconda/spydrpick.svg?style=flat
   :alt:   (downloads)
.. |docker_spydrpick| image:: https://quay.io/repository/biocontainers/spydrpick/status
   :target: https://quay.io/repository/biocontainers/spydrpick







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/spydrpick/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/spydrpick/README.html
