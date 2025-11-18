Compilation Process

======================================================== Zypher ==================================================================

g++ -E example.cpp -o example.i ( ပထမဆုံး Soruce Code ကို Header File Code in Source File) =>> preprocessor လုပ်လိုက်တေအဆင့်လို့လည်းခေါ်။

g++ -S example.i -o example.s (Convert the program to assembly code ) ===> Compiler GCC G++ 

g++ -c example.s -o example.o (Convert the assembly code into the machine code ) ==>Assembler(as) 

g++ example.o -o run.o ( Links different to Executable ) Linker 

./run.o

======================================================== Zypher ==================================================================
