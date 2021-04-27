# DJ-Compiler
Basic compiler for the Diminished Java language. Produces DISM files that can be simulated with the included sim-dism executable (run in a Linux terminal). Does not support methods. Created in C. Only the final executable version of the compiler is included in this repository to help prevent plagiarism for the class this was made for. Source code files are still available at request.
## About
This project was created over the course of several months for the COP 4620 Compilers course taught by Jay Ligatti at USF during Spring 2021. It accepts valid DJ (Diminished Java) files and performs lexical analysis, syntactic analysis, semantic analysis, and some code generation to produce a valid DISM file that can be run using the included sim-dism executable file.

**Note:** The generated DISM files do not account for functions/method calls in the DJ files and therefore functions cannot be simulated by sim-dism.
## Diminished Java
Diminished Java (DJ) was created by Jay Ligatti for the purpose of being used as the language a compiler was being made for in COP 4620.  
Documentation and examples are included in this repository in the DJ folder as well as <a href="https://www.cse.usf.edu/~ligatti/compilers/21/as1/dj/">Jay Ligatti's course web page</a>.

Documentation can also be found <a href="https://www.cse.usf.edu/~ligatti/compilers/21/as1/dj/DJ-definition.pdf">here</a>.
Good examples of DJ programs can be found <a href="https://www.cse.usf.edu/~ligatti/compilers/21/as1/dj/examples/good/">here</a>.
Bad examples of DJ programs can be found <a href="https://www.cse.usf.edu/~ligatti/compilers/21/as1/dj/examples/bad/">here</a>.
## DISM
DISM is a virtual machine with a simple, RISC-like instruction set.  
Documentation and examples are included in this repository in the DISM folder as well as <a href="https://www.cse.usf.edu/~ligatti/compilers/21/as1/dism/">Jay Ligatti's course web page</a>.

Documentation can also be found <a href="https://www.cse.usf.edu/~ligatti/compilers/21/as1/dism/DISM-definition.pdf">here</a>.
Some example programs can also be found <a href="https://www.cse.usf.edu/~ligatti/compilers/21/as1/dism/">here</a>.
