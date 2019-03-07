# spasm
An assembler for the epRISC platform

copyright John Lemme, 2016-2018 (jclemme at proportionallabs dot com)

---

## what can it do
* assembles code for epRISC platforms
* supports preprocessor defines, strings, relative positioning, local labels, etc.
* exports to binary files and verilog arrays
* generates debug files with full source vs. binary listings

## how to use
call `spasm -o output.bin input.asm` to assemble input.asm into output.bin

add `-g` flag to generate a debug file as output.bin.dbg

call `spasm --help` for all options

## build dependencies
* g++
* make
* libboost

## build instructions
1. obtain this source tree
2. install dependencies
3. run "make"
4. run "sudo make install" to install the program to your computer
   -or-
   run "make debfile" to generate a debian .deb package
