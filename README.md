
# Tic-Tac-Toe in Leo



Immerse yourself in the classic Tic-Tac-Toe game, now implemented in the Leo programming language.

## Game Board Structure
Leo's `struct` functionality is utilized to construct the game board. This `Board` struct consists of three `Row` elements. While arrays could offer an alternative structure, they are not currently supported in Leo.

## Key Features of Leo Used
- Creation of structures (`struct`)
- Implementation of conditional logic
- Function exits using `return`

## How to Run the Game

Leo's command line interface facilitates the compilation and execution of programs. Input can be provided either directly via the command line or through an input file located in `inputs/`.

### Command Line Input
1. Execute the command:
```bash
leo run <function_name> <input_1> <input_2> ...
```
Refer to `./run.sh` for an example.

### Input File
1. Alter `inputs/tictactoe.in` with the required inputs.
2. Execute the command:
```bash
leo run <function_name>
```

## Execution Command
```bash
leo execute <function_name> <input_1> <input_2> ...
```

## Gameplay Instructions

### Step 1: Initialize a New Board
```bash
leo run new
```
|   |   |   |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |

### Step 2: Player 1's Move
```bash
leo run make_move 1u8 1u8 1u8 "{ r1: { c1: 0u8, c2: 0u8, c3: 0u8 }, r2: { c1: 0u8, c2: 0u8, c3: 0u8 }, r3: { c1: 0u8, c2: 0u8, c3: 0u8 } }"
```
|   |   |   |
|---|---|---|
| 1 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |

### Step 3: Player 2's Move
```bash
leo run make_move 2u8 2u8 2u8 "{ r1: { c1: 1u8, c2: 0u8, c3: 0u8 }, r2: { c1: 0u8, c2: 0u8, c3: 0u8 }, r3: { c1: 0u8, c2: 0u8, c3: 0u8 } }"
```
|   |   |   |
|---|---|---|
| 1 | 0 | 0 |
| 0 | 2 | 0 |
| 0 | 0 | 0 |
