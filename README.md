paragrep
========

 Paragrep: print paragraph matching a pattern

 Paragrep is simmilar to grep. But instead of printing matching line, paragrep
 will print matching paragraph (one or more lines of text, separated by whitespace
 characters). Command line options are simmilar to grep:

 usage:   paragrep [-c] [-i] [-F] [-n] [-r] [-s] [-v] [-w] pattern path [path ...]


Example usage
=============

 paragrep 'eth0' /etc/network/interfaces

 paragrep -r 'Directory' /etc/apache2/sites-enabled/

 dmidecode | paragrep -i cpu

 paragrep -r -c eth0 /etc/

