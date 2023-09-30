Keycloak
========

To get help configuring Keycloak via the CLI, run:

on Linux/Unix:

    $ bin/kc.sh --http-port 9090

on Windows:

    $ bin\kc.bat --http-port 9090

To try Keycloak out in development mode, run: 

on Linux/Unix:

    $ bin/kc.sh start-dev --http-port 9090

on Windows:

    $ bin\kc.bat start-dev --http-port 9090

After the server boots, open http://localhost:9090 in your web browser. The welcome page will indicate that the server is running.

To get started, check out the [configuration guides](https://www.keycloak.org/guides#server).
