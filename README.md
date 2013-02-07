paragrep
=========

Paragrep: print paragraph matching pattern(s)


Example usages
==============

 paragrep 'eth0' /etc/network/interfaces

 paragrep -r 'Directory' /etc/apache2/sites-enabled/

 dmidecode | paragrep -i cpu

 paragrep -r -c eth0 /etc/

License
=======

Karel Kudlacek, 2013, ETH Zurich
E-Mail: karelk@ethz.ch

This is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

It is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License.
If not, see <http://www.gnu.org/licenses/>.
