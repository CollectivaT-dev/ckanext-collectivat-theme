.. image:: https://raw.githubusercontent.com/CollectivaT-dev/judeo-espanyol-resources/main/img/centered-ab-tr.png
  :align: center
  :alt: Alternative text

=============
ckanext-collectivat_theme
=============

.. Put a description of your extension here:
   What does it do? What features does it have?
   Consider including some screenshots or embedding a video!


------------
Requirements
------------

For example, you might want to mention here which versions of CKAN this
extension works with.


------------
Installation
------------

.. Add any additional install steps to the list below.
   For example installing any non-Python dependencies or adding any required
   config settings.

To install ckanext-collectivat_theme:

1. Activate your CKAN virtual environment, for example::

     . /usr/lib/ckan/default/bin/activate

2. Install the ckanext-collectivat_theme Python package into your virtual environment::

     pip install ckanext-collectivat_theme

3. Add ``collectivat_theme`` to the ``ckan.plugins`` setting in your CKAN
   config file (by default the config file is located at
   ``/etc/ckan/default/production.ini``).

4. Restart CKAN. For example if you've deployed CKAN with Apache on Ubuntu::

     sudo service apache2 reload


---------------
Config Settings
---------------

Document any optional config settings here. For example::

    # The minimum number of hours to wait before re-checking a resource
    # (optional, default: 24).
    ckanext.collectivat_theme.some_setting = some_default_value


------------------------
Development Installation
------------------------

To install ckanext-collectivat_theme for development, activate your CKAN virtualenv and
do::

    git clone https://github.com//ckanext-collectivat_theme.git
    cd ckanext-collectivat_theme
    python setup.py develop
    pip install -r dev-requirements.txt


-----------------
Running the Tests
-----------------

To run the tests, do::

    nosetests --nologcapture --with-pylons=test.ini

To run the tests and produce a coverage report, first make sure you have
coverage installed in your virtualenv (``pip install coverage``) then run::

    nosetests --nologcapture --with-pylons=test.ini --with-coverage --cover-package=ckanext.collectivat_theme --cover-inclusive --cover-erase --cover-tests


---------------------------------
Registering ckanext-collectivat_theme on PyPI
---------------------------------

ckanext-collectivat_theme should be availabe on PyPI as
https://pypi.python.org/pypi/ckanext-collectivat_theme. If that link doesn't work, then
you can register the project on PyPI for the first time by following these
steps:

1. Create a source distribution of the project::

     python setup.py sdist

2. Register the project::

     python setup.py register

3. Upload the source distribution to PyPI::

     python setup.py sdist upload

4. Tag the first release of the project on GitHub with the version number from
   the ``setup.py`` file. For example if the version number in ``setup.py`` is
   0.0.1 then do::

       git tag 0.0.1
       git push --tags


----------------------------------------
Releasing a New Version of ckanext-collectivat_theme
----------------------------------------

ckanext-collectivat_theme is availabe on PyPI as https://pypi.python.org/pypi/ckanext-collectivat_theme.
To publish a new version to PyPI follow these steps:

1. Update the version number in the ``setup.py`` file.
   See `PEP 440 <http://legacy.python.org/dev/peps/pep-0440/#public-version-identifiers>`_
   for how to choose version numbers.

2. Create a source distribution of the new version::

     python setup.py sdist

3. Upload the source distribution to PyPI::

     python setup.py sdist upload

4. Tag the new release of the project on GitHub with the version number from
   the ``setup.py`` file. For example if the version number in ``setup.py`` is
   0.0.2 then do::

       git tag 0.0.2
       git push --tags
       

.. image:: https://raw.githubusercontent.com/CollectivaT-dev/judeo-espanyol-resources/main/img/logos.png
  :align: center
  :alt: Alternative text

This repo is developed as part of project "Judeo-Spanish: Connecting the two ends of the Mediterranean" carried out by Col·lectivaT and Sephardic Center of Istanbul within the framework of the “Grant Scheme for Common Cultural Heritage: Preservation and Dialogue between Turkey and the EU–II (CCH-II)” implemented by the Ministry of Culture and Tourism of the Republic of Turkey with the financial support of the European Union. The content of this website is the sole responsibility of Col·lectivaT and does not necessarily reflect the views of the European Union. 


