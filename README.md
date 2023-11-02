# LTULIB - Custom C Preprocessor Definitions

## Project Description
**LTULIB** is a collection of custom C preprocessor definitions, designed to simplify and enhance code readability by providing alternative names for common C language constructs. This library is aimed at developers who prefer using more descriptive and user-friendly identifiers for data types, control flow, storage classes, and other language constructs in their C programs.

## Usage
To utilize the LTULIB in your C program, include the **`ltulib.h`** header file at the beginning of your source code. By doing so, you can take advantage of the defined replacements to write more expressive and intuitive code.
```c
#include "ltulib.h"
```

## Data Types
LTULIB introduces user-friendly names for common data types, making it easier to understand the purpose of variables and function parameters.

- **`sveikas`** (int): Used for integer values.
- **`ilgas`** (long): Represents long integers.
- **`trumpas`** (short): For short integers.
- **`dvigubas`** (double): Corresponds to double-precision floating-point numbers.
- **`pluduriojantis`** (float): Used for single-precision floating-point numbers.
- **`simbolis`** (char): Represents character values.
- **`su_zenklu`** (signed): Indicates signed integers.
- **`be_zenklo`** (unsigned): Denotes unsigned integers.
- **`numeruota`** (enum): For enumerations.
- **`tuscias`** (void): Represents the absence of a type.

## Control Flow
These definitions offer more human-readable alternatives for control flow statements.

- **`stabdyk`** (break): Used for breaking out of loops or switch statements.
- **`toliau`** (continue): Used to skip the current iteration and continue with the next in a loop.
- **`daryk`** (do): Begins a do-while loop.
- **`pakolei`** (while): Declares a while loop.
- **`kol`** (for): Used for loop iterations.
- **`jeigu`** (if): Starts a conditional statement.
- **`arba`** (else if): Used for additional conditional branches in an if statement.
- **`kitais_atvejais`** (else): Provides an alternative condition in an if statement.
- **`eik`** (goto): Transfers control to a labeled statement within the same function.
- **`kaitaliok`** (switch): Starts a switch statement.
- **`grazink`** (return): Exits a function and returns a value.

## Storage Classes
These alternatives simplify the declaration of variables with various storage classes.

- **`automatiskai`** (auto): Automatically allocated local variables.
- **`konstanta`** (const): Denotes constant values.
- **`iskelti`** (extern): Declares variables that are defined in other files.
- **`registruok`** (register): Suggests that a variable should be stored in a CPU register.
- **`statinis`** (static): Indicates static variables with limited scope.

## Function and Program Flow
These definitions enhance readability related to function and program flow.

- **`atvejis`** (case): Used within a switch statement to define case labels.
- **`iprasta`** (default): Provides a default case within a switch statement.
- **`dydis`** (sizeof): Computes the size of a data type or expression.
- **`pakeist`** (typedef): Defines custom data type aliases.

## Structures and Unions
These names improve the understanding of structures and unions.

- **`struktura`** (struct): Declares a structure.
- **`sajunga`** (union): Declares a union.

## Other
- **`nepastovus`** (volatile): Indicates that a variable's value can be changed by external factors.

## Compatibility
It's important to note that while LTULIB can enhance code readability, it might not be standard across all C compilers. Developers should consider the compatibility of these custom definitions with their specific toolchain and project requirements.

## Conclusion
LTULIB aims to make C programming more accessible and expressive by providing intuitive and descriptive alternatives to standard C language constructs. Developers can choose to include this library in their projects to improve code readability and maintainability.

Please remember to use these definitions judiciously and consider your team's coding standards and project requirements when incorporating them into your C programs.

