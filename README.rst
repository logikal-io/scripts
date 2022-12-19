Scripts
=======
Common system scripts.

Requirements
------------
The `Google Cloud Command Line Interface <https://cloud.google.com/cli>`_ needs to be installed for
the ``gcpl`` script to work.

The `AWS Command Line Interface <https://aws.amazon.com/cli/>`_ and `jq
<https://stedolan.github.io/jq/>`_ needs to be installed for the ``awsl`` script to work.

Installation
------------
Simply clone the repository and add the ``bin`` folder to your system path:

.. code-block:: shell

    git clone git@github.com:logikal-io/scripts.git ~/.logikal-scripts
    echo 'PATH="$PATH:$HOME/.logikal-scripts/bin"' >> ~/.bash_aliases

License
-------
This repository is licensed under the MIT open source license.
