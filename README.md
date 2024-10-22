# SIC Assembler

## Overview

This project is a SIC (Simplified Instructional Computer) assembler that translates assembly language code into object code.

## Features

- Assembles SIC assembly language code into machine code
- Generates object files compatible with SIC architecture
- Supports basic SIC instructions and directives


## Usage

1. **Clone the repository**
2. **compile the main.c using gcc compiler**
    ```terminal/bash
    cd src
    gcc main.c -o reader.exe
    mv reader.exe ..

3. **run by adding SIC assembly code and the output file**  
    ```terminal/bash
    ./program.exe input.asm output.obj
