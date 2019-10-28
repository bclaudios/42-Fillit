# 42 - Fillit
42's fourth project - A software that assemble a given tetriminos set altogether in the smallest possible square.
## Subject
Fillit [subject](./fillit.en.pdf)
## Grade
100/100 ✅ (12-13-2018)
## Languages
- C
## Usage
```
make                    // Compile the software
./fillit your_map_here  // Test the map passed as an argument. You can find test maps in the /maps folder.

MAKEFILE RULES
make          // Compile the software
make clean    // Delete all .o files
make fclean   // Delete all .o files and the compiled software
make re       // make fclean && make
