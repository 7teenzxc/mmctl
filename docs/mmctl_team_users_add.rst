.. _mmctl_team_users_add:

mmctl team users add
--------------------

Add users to team

Synopsis
~~~~~~~~


Add some users to team

::

  mmctl team users add [team] [users] [flags]

Examples
~~~~~~~~

::

    team add myteam user@example.com username

Options
~~~~~~~

::

  -h, --help   help for add

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --config string                path to search for '.mmctl' configuration file (default "$HOME/.config/mmctl")
      --format string                the format of the command output [plain, json] (default "plain")
      --insecure-sha1-intermediate   allows to use insecure TLS protocols, such as SHA-1
      --local                        allows communicating with the server through a unix socket
      --strict                       will only run commands if the mmctl version matches the server one

SEE ALSO
~~~~~~~~

* `mmctl team users <mmctl_team_users.rst>`_ 	 - Management of team users

