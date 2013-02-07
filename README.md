paragrep
=========

 Paragrep: print paragraph matching pattern(s)

 Paragrep is similar to grep. But instead of printing matching line, paragrep
 will print matching paragraph (one or more lines of text, separated by whitespace
 characters). When multiple search patterns are provided, paragrep will print 
 paragraphs matching all patterns. Command line options are similar to grep:

 usage:   paragrep [-c] [-i] [-n] [-r] [-s] [-v] [-w] pattern [pattern ...] path

Example usage
=============

 paragrep 'eth0' /etc/network/interfaces

 paragrep -r 'Directory' /etc/apache2/sites-enabled/

 dmidecode | paragrep -i cpu

 paragrep -r -c eth0 /etc/

License
=======

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
