**************************
 A Home ``bin`` Directory
**************************

This is my own ``bin`` directory, using the Stupid Buildout Trick™ of turning
your home ``bin`` directory into a Buildout_.

No sane person does this in practice, hence my sobriquet "nutjob4life".


To Use
======

Do the usual::

    cd ~
    git clone https://github.com/nutjob4life/bindir.git bin
    cd bin
    python3 bootstrap.py
    ./buildout


.. _Buildout: https://pypi.org/project/zc.buildout/1.5.2/#install-egg-based-scripts
