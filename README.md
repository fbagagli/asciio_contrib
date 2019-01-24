Readme
======

This repository contains additions to the Asciio perl program:

https://metacpan.org/pod/App::Asciio

Installation
============

Ubuntu
------

Install asciio from apt

.. code:: shell

    sudo apt install asciio

Then update the config file and add the needed stencils (from readme folder)

.. code:: shell

    $ sudo ln -s -b $(pwd)/setup.ini /usr/share/perl5/App/Asciio/setup/setup.ini
    $ sudo ln -s -b $(pwd)/stencils/circuit /usr/share/perl5/App/Asciio/setup/stencils/circuit

