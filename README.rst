=========
PsrSigSim
=========


.. image:: https://img.shields.io/pypi/v/psrsigsim.svg
        :target: https://pypi.python.org/pypi/psrsigsim

.. image:: https://github.com/PsrSigSim/PsrSigSim/workflows/PsrSigSim%20Build/badge.svg?branch=master
        :target: https://github.com/PsrSigSim/PsrSigSim/actions

.. image:: https://readthedocs.org/projects/psrsigsim/badge/?version=latest
        :target: https://psrsigsim.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

.. image:: https://joss.theoj.org/papers/6f2caac6394c899d461075963b5d7e45/status.svg
        :target: https://joss.theoj.org/papers/6f2caac6394c899d461075963b5d7e45

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.4521235.svg
        :target: https://doi.org/10.5281/zenodo.4521235

The NANOGrav Pulsar Signal Simulator
------------------------------------

* Free software: MIT license
* Documentation: https://psrsigsim.readthedocs.io.

.. image:: https://raw.githubusercontent.com/PsrSigSim/PsrSigSim/master/pss_logo.jpg
        :align: center

Image Credit: Caitlin Witt

The Pulsar Signal Simulator (`PsrSigSim`) is a Python package developed by the
North American Nanohertz Observatory for Gravitational Waves (NANOGrav). This
software is free to use and is designed as a tool for simulating realistic
pulsar signals, as well as educating students and researchers about those
signals. Various models from the copious pulsar literature are used for
simulating emission, propagation effects and data processing artifacts.

Goals
-----

* **Investigate sources of time-of-arrival errors:** Simulate various sources of time of arrival errors, including interstellar medium effects, intrinsic pulsar noise, various pulsar emission mechanisms and gravitational waves. Simulate instrumental noise sources, including radio frequency interference, radiometer noise and backend sampling effects.
* **Education and Outreach:** Allow users to build pulsar signals piece-by-piece to demonstrate to students how pulsar signals change as they propagate and how they are changed by the signal processing done at the telescope. Make materials for talks and outreach including signal diagrams and sound files of sonified pulsars.
* **Search algorithms and search training:** Test new search algorithms on signals with known parameters. Use simulated signals for search training. Assess the sensitivity of current search algorithms with simulated signals.

Code of Conduct
---------------
The `PsrSigSim` community expects contributors to follow a `Code of Conduct`_ outlined with our documentation.

Credits
-------
Development Team: Jeffrey S. Hazboun, Brent Shapiro-Albert, Paul T. Baker

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _`Code of Conduct`: https://psrsigsim.readthedocs.io/en/latest/code_of_conduct.html
.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
