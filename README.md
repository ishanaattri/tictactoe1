
# Tic-Tac-Toe in Leo

Game Board Structure

Utilizing Leo's struct functionality, the game board is meticulously constructed. The Board struct comprises three Row elements. Although arrays could serve as an alternative structure, they are presently unsupported in Leo.

Key Features of Leo Utilized

Creation of structures (struct)
Implementation of conditional logic
Function exits using return
How to Run the Game

Leo's command line interface simplifies the compilation and execution of programs. Input can be furnished either directly via the command line or through an input file situated in inputs/.

Command Line Input

Execute the following command:
leo run <function_name> <input_1> <input_2> ...
Consult ./run.sh for a illustrative example.

Input File

Modify inputs/tictactoe.in with the requisite inputs.
Execute the command:
leo run <function_name>

Execution Command
leo execute <function_name> <input_1> <input_2> ...

Gameplay Instructions

Step 1: Initialize a New Board
leo run new

0    0    0
0    0    0
0    0    0
Step 2: Player 1's Move
leo run make_move 1u8 1u8 1u8 "{ r1: { c1: 0u8, c2: 0u8, c3: 0u8 }, r2: { c1: 0u8, c2: 0u8, c3: 0u8 }, r3: { c1: 0u8, c2: 0u8, c3: 0u8 } }"


1    0    0
0    0    0
0    0    0
Step 3: Player 2's Move
leo run make_move 2u8 2u8 2u8 "{ r1: { c1: 1u8, c2: 0u8, c3: 0u8 }, r2: { c1: 0u8, c2: 0u8, c3: 0u8 }, r3: { c1: 0u8, c2: 0u8, c3: 0u8 } }"


1    0    0
0    2    0
0    0    0






