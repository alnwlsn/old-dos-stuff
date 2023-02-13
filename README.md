# old-dos-stuff
Trying to compile programs for my really old MS-DOS machines

## bc
BC (bench calculator) is an arbitrary-precision calculator language for UNIX. I used the GNU version, and got it to work by adding all the .c and .h files in Open Watcom and fixing a lot of include errors.
Only thing I really had to change was a call for random() to a call for rand(). Not sure if that's the same thing though. Seems to work OK, but runs out of memory for really big numbers.
