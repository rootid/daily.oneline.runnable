

Which Java files have not been changed in the last week?

find . -name '*.java' -mtime +7 -print


Construct a zip/tar archive of my source.

zip archive.zip *.h *.c 

-or- 

tar cvf archive.tar *.h *.c




Find all .c files modified more recently than your Makefile.

find . -name ' *.c' -newer Makefile -print





