Collector for ACLED’s Datasets
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

|Build Status| |Coverage Status|

Collector designed to collect the conflict datasets from the `ACLED`_
website.

Usage
~~~~~

::

    python run.py

You will need to have a file called .hdxkey in your home directory
containing only your HDX key for the script to run. The script
was created to automatically register datasets on the `Humanitarian Data
Exchange`_ project.

.. _ACLED: http://www.acleddata.com/
.. _Humanitarian Data Exchange: http://data.humdata.org/

.. |Build Status| image:: https://travis-ci.org/OCHA-DAP/hdxscraper-acled.svg?branch=master&ts=1
    :target: https://travis-ci.org/OCHA-DAP/hdxscraper-acled
.. |Coverage Status| image:: https://coveralls.io/repos/github/OCHA-DAP/hdxscraper-acled/badge.svg?branch=master&ts=1
    :target: https://coveralls.io/github/OCHA-DAP/hdxscraper-acled?branch=master
