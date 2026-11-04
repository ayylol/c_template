# Bimgus C template

Skeleton C project to use as a quick and general starting point.

The makefile compiles everything in the src directory up to two subdirectories
down. It also includes those directories.

Default executable name is `a.out`, remember to change it!

includes targets:
- `all` compiles the program in debug mode
- `debug`/`release` compiles the program, adding the appropriate flags
- `clean` removes the build directory and the executable
- `remake` runs clean and then compiles in the default mode (debug)
- `remake-dbg` same as remake
- `remake-rel` same as remake, but compiles in release mode
- `echo` prints out the relevant files


