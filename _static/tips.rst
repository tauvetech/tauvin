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

Pour faire un nettoyage de docker exécutez ces deux commandes::

  docker rm $(docker ps -a -q)
  docker rmi $(docker images -q)

Une fois fini Docker est propre comme si de rien n'était :)
