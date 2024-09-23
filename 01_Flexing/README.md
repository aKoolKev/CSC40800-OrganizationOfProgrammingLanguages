# CSC40800-Fall2024


## Run Instructions (for main C++ code in lex file)
1. `Flex++` <fileName.l>
    - Will produce a `lex.yy.cc` file
2. `g++ lex.yy.cc`
    - Will produce a `a.out` executable
3. `./a.out`


## Run Instructions (for seperated main file)
1. `Flex++` <fileName.l>
    - Will produce a `lex.yy.cc` file

2. `g++ -c -Wall -ansi -pedantic -std=c++20 lex.yy.cc`
    - Will produce an object lex file: `lex.yy.o`

3. `g++ -c -Wall -ansi -pedantic -std=c++20 main.cpp`
    - Will produce an main object file: `main.o`

4. `g++ -o exeName main.o lex.yy.o`
    - Will produce an executable: `exeName`


