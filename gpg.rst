GnuPG
=====


Geração de chaves
--------------------

Basta executar o comando::

  gpg --gen-key
  
Caso demore, abra outro terminal, instale e execute `os comandos abaixo <https://www.thingy-ma-jig.co.uk/blog/22-01-2010/generate-entropy-gnupg>`_::

  sudo apt-get install -y rng-tools
  sudo /usr/sbin/rngd -r /dev/urandom
  
Para ver mais opções do gpg, execute o comando com a opção --help::

  gpg --help
  
