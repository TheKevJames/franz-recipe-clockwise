Franz Recipe for Clockwise
==========================

This recipe allows you to integrate `Franz`_ with `Clockwise`_. It also works
with `Ferdium`_, the community-maintained Franz fork.

Installation
------------

#. Create a plugins folder on your machine, if it does not exist yet. Replace
   ``<APP>`` with either ``"Franz"`` or ``"Ferdium"``:

   - Linux: ``~/.config/<APP>/recipes/dev/``
   - Mac: ``~/Library/Application Support/<APP>/recipes/dev/``
   - Windows: ``%APPDATA%/<APP>/recipes/dev/``

   where ``~`` is your home directory, eg:

   - Linux: ``/home/kevin``
   - Mac: ``/Users/kevin``
   - Windows: ``C:/Users/kevin/AppData/Roaming``

#. Copy this repo into the above folder, named ``clockwise``:

   - if you have ``git``, run: ``git clone git@github.com:TheKevJames/franz-recipe-clockwise.git ~/.config/<APP>/recipes/dev/clockwise``
   - otherwise, grab the latest `zip file`_ and unzip it into the above
     folder, then rename it to ``clockwise``

#. Reload Franz/Ferdium

Updating
--------

If you used ``git`` in the installation step, simply navigate to that folder
and run ``git pull``.

If not, you'll need to repeat the installation procedure from scratch, deleting
the folder you created the previous time around.

.. _Clockwise: https://www.getclockwise.com/
.. _Ferdium: https://ferdium.org/
.. _Franz: https://meetfranz.com/
.. _zip file: https://github.com/TheKevJames/franz-recipe-clockwise/archive/master.zip
