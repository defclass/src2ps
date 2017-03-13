# src2ps

a handy cmd to convert source code to PostScript

# Usage
* Require install `enscript`.

* Download the `src2ps` shell script into executable directory.

* Add exeute privilege on `src2ps`, `chomd +x src2ps`.

* Change current source directory `cd /path/to/need/to/combine`

* `src2ps /tmp/XXX.ps java`


# Configure

* Add TOC format: 

  vim `/etc/enscript/enscript.cfg`

  uncomment line which contains string `TOCFormat`

  update to `TOCFormat: $3v P: $3%  L: $4L $-40N`

