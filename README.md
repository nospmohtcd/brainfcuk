# brainfcuk
Contains a brainfuck interpreter written in the Scientific Vector Language (SVL) along with a series of *.b files for use with the interpreter. The examples were taken from a number of places online, and are attributed below. 

custom/sample
├── beer.b : 99 bottles of beer on the wall - jim crawford (http://www (dot) goombas (dot) org/)
├── brainfuck.b : Well, you did ask
├── e.b : https://www.brainfuck.org/
├── hello.b : Obligatory
├── random.b : https://esoteric.sange.fi/brainfuck/bf-source/prog/
├── selfportrait.b : https://esoteric.sange.fi/brainfuck/bf-source/quine/
├── sierpinski.b : https://www.brainfuck.org/
└── squares.b : https://www.brainfuck.org/

With a valid MOE license it is enough to run the following at the command line:

$MOE/bin/moebatch -stdc -custom custom -exec "input = tok_cat [MOE_PATH_CUSTOM, '/sample/hello.b']; brainfuck_interpreter [file:input]"
