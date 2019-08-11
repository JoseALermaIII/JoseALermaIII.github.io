JoseALermaIII.github.io
=======================
Professional tinkerer, part-time nerd, full-time geek.

GitHub Projects
===============

This is a summary of my projects on GitHub.

A sort of appendix to my main website: `JoseALerma.com`_

.. _JoseALerma.com: https://JoseALerma.com

clashcallerbot-reddit
---------------------

`ClashCallerBot`_ was made to help `/r/ClashOfClans <https://np.reddit.com/r/ClashOfClans>`_ clans coordinate attacks
during `Clan Wars <https://clashofclans.fandom.com/wiki/Clan_Wars>`_ (or `Clan War Leagues
<https://clashofclans.fandom.com/wiki/Clan_War_Leagues>`_) from within reddit.

It uses Python and PRAW to read incoming comments from reddit, scan them for a particular string, comments a confirmation receipt,
saves pieces of that string to a MySQL or MariaDB database along with a caluclated reminder time, then checks the reminder time
from the database and PMs a reminder to the user.

The `Docs <https://josealermaiii.github.io/clashcallerbot-reddit/>`_ offer more details about usage, installation, and frequently
asked questions.

.. _ClashCallerBot: https://github.com/JoseALermaIII/clashcallerbot-reddit

python-tutorials
----------------

`python-tutorials`_ is a collection of resources to learn the Python programming language. Resources include books and
online courses.

This repo became very nested very quickly, so newer resource materials I use have their own repo (keep reading to see more).
For more information about this repo, check out the `Docs <https://josealermaiii.github.io/python-tutorials/>`_.

The `Docs <https://josealermaiii.github.io/python-tutorials/getting_started/installation.html>`_ also include information 
about configuring a Python environment/IDE.

.. _python-tutorials: https://github.com/JoseALermaIII/python-tutorials

If you're reading this, mention "Gravity Falls"
-----------------------------------------------

It's been about 4 years, but I'm actually starting to get random e-mails from people that scrape GitHub. So far, they're 
super-generic, "I'm _____ from github.com"

Gravity Falls is a good TV show. You can e-mail me a rebuttal, if you want. Either way, it'll show you've at least read 
this far.

...not that I want you to read this any further...BAKA! \*runs\*

automatepracticeprojects
------------------------

`automatepracticeprojects`_ is one of the resources from `python-tutorials`_ that got its own repo. They're example implementations 
of the practice projects in `Automate the Boring Stuff with Python`_. It showcases basic Python conventions like pip 
requirements files and Google-style docstrings. 

Honestly, the version in the `python-tutorials`_ repo's 
`Docs <https://josealermaiii.github.io/python-tutorials/AutomateTheBoringStuff.html>`_ is better.

.. _Automate the Boring Stuff with Python: https://automatetheboringstuff.com/

impracticalpythonprojects
-------------------------

Saved the best (so far) for last!

`impracticalpythonprojects`_ is the first resource that got its own repo. They're example
implementations of the practice and challenge projects in `Impractical Python Projects`_.

The practice and challenge projects are *truly* impractical, but they teach useful data analysis and processing techniques.

The repo showcases more intermediate Python conventions and modules like:

* extensive testing with ``unittest``, ``tox``, and `Travis-CI`_.
* 100% `code coverage`_ with ``coverage`` and ``coveralls``.
* linting with ``pylint`` and ``pydocstyle``.
* `documentation`_ with ``sphinx``.

and the usual Google-style docstrings, pip requirements files, and main functions.

.. _impracticalpythonprojects: https://github.com/JoseALermaIII/impracticalpythonprojects
.. _Impractical Python Projects: https://nostarch.com/impracticalpythonprojects
.. _Travis-CI: https://travis-ci.com/JoseALermaIII/impracticalpythonprojects
.. _code coverage: https://coveralls.io/github/JoseALermaIII/impracticalpythonprojects?branch=master
.. _documentation: https://josealermaiii.github.io/impracticalpythonprojects/
