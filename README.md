paragrep
========

 Paragrep works like grep, but instead of printing matching line, it prints matching paragraph.
 By default, paragraphs are separated by empty line, but custom delimiter can be specified.

 Command line options are similar to grep:

```
 paragrep [-A num] [-B num] [-C num] [-F] [--color] [-c] [--delimiter='string'] [-i] [-l] [-n] [-r] [-s] [-v] [-w] pattern FILE [FILE ...]
```

Example usage
=============

```
 paragrep eth0 /etc/network/interfaces

 paragrep -r 'Directory' /etc/apache2/sites-enabled/

 dmidecode | paragrep -i cpu

 lspci -v | paragrep iwlwifi
```
