Bcfg2 - Sample Repository
-------------------------

The Bcfg2 sample repository contains example files for various Bcfg2
generators and plugins.  Those files may not work in your environment
without manual configuration.  Others can be obsolete from time to time.
The only purpose is to give you a entry point for your own configuration.

How to use
----------

1. Browse the samples online
Just visit https://github.com/solj/bcfg2-repo and see what's inside the
example repository.

2. Browse the samples offline
If git is installed on your system then you can clone the complete sample
repository to your local harddrive.::

    git clone https://github.com/solj/bcfg2-repo.git

3. Use the data to start your own Bcfg2 repository from the beginning
After running 'bcfg2-admin init' your Bcfg2 respository contains only a
few files. Before you proceed with the next step, make a backup of your
exisiting files in the local Bcfg2 repository (e.g. ``/var/lib/bcfg2``).

You can delete the whole directory and pull a copy of all Bcfg2 sample
files. This operation needs to be run as root (provided this is the user
you are using to run the Bcfg2 server).::

    cd /var/lib/ && rm -rf bcfg2
    git clone https://github.com/solj/bcfg2-repo.git bcfg2

We recommend to put your local Bcfg2 repository under the control of git.
For more detail please refer to the following wiki page:
http://bcfg2.org/wiki/ExampleRepository

Want to contribute
------------------

Do you have a configuration which could be useful for others? Do you
want to share your knowledge with the community? The easiest way to get
your stuff integrated is to fork the git respository and to place a pull
request. For more details check http://bcfg2.org/wiki/Bcfg2GitHowto

Need help
---------

* Homepage:      http://bcfg2.org
* Wiki:          http://bcfg2.org/wiki/
* Manual:        http://docs.bcfg2.org/
* IRC:           #bcfg2 on chat.freenode.net
* Mailing list:  https://lists.mcs.anl.gov/mailman/listinfo/bcfg-dev
* Bug tracker:   http://bcfg2.org/report

Bcfg2 samples are licensed under BSD, for more details check COPYING.
