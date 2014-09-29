 
isoread
=======

Extract all the files in an ISO via isoread. No need for root access.

FYI 7z can also do the same (as can fuse) but this tool depends only on isoread
 
Usage: isoread -i <file> -o <outdir>
 
    -i
    -iso
    --iso <imagename>   : Name of ISO to read.

    -o
    -out
    --out <dir>         : Directory to extract to.

    -d
    -debug
    --debug             : Debug

(based on http://korenofer.blogspot.mx/2008/08/how-to-extract-iso-file-with-bash-shell.html)
