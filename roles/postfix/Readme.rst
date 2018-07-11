.. role:: bash(code)
:language: bash

======
README
======

postfix usage description
created by spamcomm@gmail.com
# TODO: add description below


Testing
-------
Before testing user has to  :code:`cd ./postfix_example/postfix/ci/testing_method` where testing_method is either
 - vagrant
 - docker

- If using Test-Kitchen:

.. code-block:: bash
    $cd ./postfix_example
    $ bundle install
    $ kitchen test

- If using Molecule:

.. code-block:: bash
    $ pip install -r ./postfix_example/requirements.txt
    $ molecule test