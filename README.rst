gitproj
=======

:Author:	Ryan Corpuz
:Source:	https://github.com/RyanCorpuz/gitproj
:Version: 1.0
One paragraph of project description goes here

Setup
------------
Installing gitproj:

   ::

      $  git clone git://github.com/RyanCorpuz/gitproj.git

Next is to edit *secret* script

   ::

      GIT_USERNAME=<USERNAME>
      GIT_API_TOKEN=<API TOKEN>
      AUTHOR=<AUTHOR>

Where:
   *  <USERNAME> is your github username
   *  <API TOKEN> is your Personal Token with the right permissions. Credit `here <https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line>`_ for instructions for creating a token
   *  <AUTHOR> is the name you wish to show as author in your README.rst

Lastly, move your *gitproj* and *secret* to your bin.

Usage
-----

   ::

         Usage: gitproj [option] [repo name]

            -h, --help               show help text
            -p, --private            make repo private   

         Create github repo with current name

Example Use
To make a local directory and a github repo called *myproject*:

   ::
   
      $ gitproj myproject

This yields the following directory structure (local and github repo):

   ::

      myproject
      |-README.rst

End with an ex of getting some data out of the system or using it for a little demo

License
-------
gitproj is licensed under the terms of the MIT License. See `LICENSE`_ file.

_LICENSE: https://github.com/RyanCorpuz/gitproj/blob/master/LICENSE
