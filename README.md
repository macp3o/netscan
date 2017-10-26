# Linux Netscan for Dell 1600n

_Linux network scan utility for the Dell 1600n network printer/scanner_


## Quick Start
1. Copy the files
2. Create directory `/home/team`
3. Run `sudo netscan pdf team`

Alternative options include: tiff and jpeg. Jpeg scans in color, but at lower resolution.

For saving scans to the current folder, run `sudo netscan pdf here`

## Customization
The `team` directory is hardwired in the  Perl source, and it can be changed.

# Init.d Installation
`Netscan` was designed to be installed as an `/etc/init.d` script,
and it reponds to standard `start`, `stop`, `restart`, and `status`.

When installed as an `init.d` script, `netscan`starts in the the last used scan mode,
i.e. pdf, tiff, or jpeg.

## Credits and License
`dell1600n-net-scan.pl` is open source graciously contributed by [Jon Chambers](http://www.jon.demon.co.uk/), and customized by me. See the license included within the file `dell1600n-net-scan.pl`. The original source code is available at http://www.jon.demon.co.uk/dell1600n-net-scan/

All other code: MIT license. See the LICENSE file for details. 



