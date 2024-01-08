# Monkey Interpreter in Go

## Description

Welcome to the Monkey Interpreter in Go project, a hands-on endeavor inspired by Thorsten Ball's book, "Writing An Interpreter In Go." This project aims to implement an interpreter for the Monkey programming language, following the principles and lessons laid out in the book. By engaging in this journey, you'll gain a deeper understanding of language design, parsing, and interpreter construction.
If you want to get a copy you can find one at:
https://interpreterbook.com/

## Features

- Lexer and Parser for Monkey language
- Abstract Syntax Tree (AST) representation
- Interpreter for executing Monkey code
- REPL (Read-Eval-Print Loop) for interactive usage

## Getting Started

### Prerequisites

- Go installed on your machine

### Installation

1. Clone the repository: `git clone https://github.com/eugen252009/monkey-interpreter.git`
2. Navigate to the project directory: `cd monkey-interpreter`
3. Build the project: `go build`

### Usage

1. Run the REPL: `./monkey-interpreter`
2. Enter Monkey code in the REPL prompt and see it interpreted in real-time.

```monkey
>> let x = 5;
>> let y = 10;
>> let result = add(x, y);
>> result
```

### Licence
Copyright (c) 2024 Eugen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
