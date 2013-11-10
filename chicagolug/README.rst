===============================
chicagolug
===============================

Website of the Chicago GNU/Linux User Group


Quickstart
----------

::

    git clone https://github.com/j1mc/chicagolug
    cd chicagolug
    pip install -r requirements/dev.txt
    export CHICAGOLUG_ENV='dev'
    python manage.py createdb
    python manage.py runserver


Shell
-----

To open the interactive shell, run ::

    python manage.py shell

By default, you will have access to ``app``, ``models``, and ``db``.

Development / Production Environments
-------------------------------------

Configuration environements are handled through the CHICAGOLUG_ENV system environment variable.

To switch to the development environment, set ::

    export CHICAGOLUG_ENV="dev"

To switch to the production environment, set ::

    export CHICAGOLUG_ENV="prod"