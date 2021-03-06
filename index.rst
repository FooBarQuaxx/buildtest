.. BuildTestDocs documentation master file, created by
   sphinx-quickstart on Tue Apr  4 07:54:15 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

buildtest - Software Testing Framework
=========================================

Welcome to buildtest_ documentation. buildtest is a HPC Application Testing
Framework designed to build tests quickly and verify an entire HPC software stack

This documentation was last rebuild on |today| and is intended for version |version|.

Introduction to buildtest
-------------------------

.. toctree::
   :glob:
   :maxdepth: 2

   What_is_buildtest
   Architecture

Getting Started
---------------

.. toctree::
   :maxdepth: 2

   Setup
   Buildtest_Variables
   How_to_use_BuildTest
   Show_Configuration
   scan_test
   List_Subcommand
   Find_Operations
   diff_trees

Building tests
-----------------

.. toctree::
   :maxdepth: 2

   Build_Subcommand
   Shell
   r_package_testing
   python_package_testing
   perl_package_testing
   ruby_package_testing

Running tests
--------------

.. toctree::
   :maxdepth: 2

   Run_Subcommand
   module_load_test

binarytest yaml configuration
-------------------------------

.. toctree::
   :maxdepth: 2

   Yaml_Subcommand
   BinaryTest_Yaml_Application
   BinaryTest_Yaml_SystemPackages

buildtest YAML Framework
------------------------

.. toctree::
   :maxdepth: 2

   show_yaml_keys
   Writing_Test_In_YAML
   MPI_yaml
   OpenMP_yaml
   Jobscript_yaml_configuration


Jobscript Features
------------------

.. toctree::
   :maxdepth: 2

   Job_Template
   Automate_BatchJobs

Additional Features
--------------------

.. toctree::
    :maxdepth: 2

    EasyBuild_Integration
    OHPC_Integration





Useful Links
-------------
* buildtest_ - The buildtest documentation
* buildtest-framework_ - The buildtest Testing framework
* buildtest-configs_ - buildtest YAML configs for generic apps
* R-buildtest-config_ - R test scripts repository
* Perl-buildtest-config_ - Perl test scripts repository
* Python-buildtest-config_ - Python test scripts repository
* Ruby-buildtest-config_ - Ruby test scripts repository

Join the buildtest slack channel (hpcbuildtest.slack.com) to get connected
with the community. To join this channel please email **shahzebmsiddiqui@gmail.com**

.. _buildtest: https://github.com/HPC-buildtest/buildtest
.. _buildtest-framework: https://github.com/HPC-buildtest/buildtest-framework
.. _buildtest-configs: https://github.com/HPC-buildtest/buildtest-configs
.. _R-buildtest-config: https://github.com/HPC-buildtest/R-buildtest-config
.. _Perl-buildtest-config: https://github.com/HPC-buildtest/Perl-buildtest-config
.. _Python-buildtest-config: https://github.com/HPC-buildtest/Python-buildtest-config
.. _Ruby-buildtest-config: https://github.com/HPC-buildtest/Ruby-buildtest-config



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
