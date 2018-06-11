tips
====

some tips often used ...

Git::

   git reset --soft HEAD^ (annuler un commit).
   git reset HEAD <fichier> (desindexer un fichier).
   git grep -En <expresssion> (search in git)

OPENOCD::

   fichier dans openocd/contrib (rules).

linux commands::

   find . -name *.sh -exec chmod +x {}\;
                *.py
   grep -r <expresssion>
   grep -REn <expresssion>

vider la corbeille (sudo)::

   sudo rm -rf ~/.local/share/Trash/files/*

Docker
------

for a cleaning docker environment, execute the following commands:

  docker rm $(docker ps -a -q)
  docker rmi $(docker images -q)

Once finished, it's OKay :)

update-alternatives
-------------------

choose compiler default (once installed):

  sudo update-alternatives --config gcc

set date over SSH
-----------------

  ssh user@server sudo date -s @`( date -u +"%s" )`

