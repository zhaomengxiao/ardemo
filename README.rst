ARDemo
===============================

.. image:: https://github.com/zhaomengxiao/ardemo/raw/master/project-icon.png
   :height: 128px
   :width: 128px
   :target: https://github.com/zhaomengxiao/ardemo
   :alt: Logo

.. image:: https://github.com/zhaomengxiao/ardemo/badges/master/build.svg
   :target: https://github.com/zhaomengxiao/ardemo/pipelines
   :alt: GitLab-CI test status

.. image:: https://github.com/zhaomengxiao/ardemo/badges/master/coverage.svg
    :target: https://github.com/zhaomengxiao/ardemo/commits/master
    :alt: Test coverage

.. image:: https://readthedocs.org/projects/ardemo/badge/?version=latest
    :target: http://ardemo.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status



Author: Zhao Youjun

ARDemo is part of the `SciKit-Surgery`_ software project, developed at the `Wellcome EPSRC Centre for Interventional and Surgical Sciences`_, part of `University College London (UCL)`_.

ARDemo is tested on Python 3.7 but should support other modern Python versions.

ARDemo is currently a demo project, which will add/multiply two numbers. Example usage:

::

    python ardemo.py 5 8
    python ardemo.py 3 6 --multiply

Please explore the project structure, and implement your own functionality.

Developing
----------

Cloning
^^^^^^^

You can clone the repository using the following command:

::

    git clone https://github.com/zhaomengxiao/ardemo


Running tests
^^^^^^^^^^^^^
Pytest is used for running unit tests:
::

    pip install pytest
    python -m pytest


Linting
^^^^^^^

This code conforms to the PEP8 standard. Pylint can be used to analyse the code:

::

    pip install pylint
    pylint --rcfile=tests/pylintrc ardemo


Installing
----------

You can pip install directly from the repository as follows:

::

    pip install git+https://github.com/zhaomengxiao/ardemo



Contributing
^^^^^^^^^^^^

Please see the `contributing guidelines`_.


Useful links
^^^^^^^^^^^^

* `Source code repository`_
* `Documentation`_


Licensing and copyright
-----------------------

Copyright 2023 Zhao Youjun.
ARDemo is released under the BSD-3 license. Please see the `license file`_ for details.


Acknowledgements
----------------

Supported by `Wellcome`_ and `EPSRC`_.


.. _`Wellcome EPSRC Centre for Interventional and Surgical Sciences`: http://www.ucl.ac.uk/weiss
.. _`source code repository`: https://github.com/zhaomengxiao/ardemo
.. _`Documentation`: https://ardemo.readthedocs.io
.. _`SciKit-Surgery`: https://github.com/SciKit-Surgery
.. _`University College London (UCL)`: http://www.ucl.ac.uk/
.. _`Wellcome`: https://wellcome.ac.uk/
.. _`EPSRC`: https://www.epsrc.ac.uk/
.. _`contributing guidelines`: https://github.com/zhaomengxiao/ardemo/blob/master/CONTRIBUTING.rst
.. _`license file`: https://github.com/zhaomengxiao/ardemo/blob/master/LICENSE

