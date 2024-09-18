# C0-Compiler
A compiler that converts C0 code (a simplified C dialect) into MIPS assembly.

To run you have to install cabal, be outside of /src and write (in this order):
cabal update
cabal build
cabal run
and then give it some c0 code (or c and see if it recognizes) then you ctrl-d to simulate end of file.
