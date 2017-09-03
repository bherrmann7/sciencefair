# sciencefair

A science fair web site.   Built for the first science fair for the Groton Dunstable Elementary School.  Mostly for sharing information and registration.

## Prerequisites

You will need [Leiningen][1] 2.0 or above installed.

[1]: https://github.com/technomancy/leiningen

## Partial instructions for setting up development on a new mac

    1  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    2  brew search mysql
    3  brew install homebrew/versions/mysql56
    4   /usr/local/opt/mysql56/bin/mysql.server start
    5  history
    6  history > sciencefair.on.newmac.txt

    install jdk

    install intellij 

## Running

To start a web server for the application, run:

    lein ring server

## License

Copyright © 2014 Bob Herrmann

