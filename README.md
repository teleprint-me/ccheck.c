# ccheck

**ccheck** is a minimalist testing framework written in pure C, designed to provide simple and efficient unit tests for C projects.

## Features

- Lightweight, minimal dependencies
- Simple interface for defining and running tests
- Designed for ease of integration into any C project

## Dependencies

- logger: A simple and lightweight logger written in pure C
- float_is_close: Compare floating-point numbers with a given tolerance in C

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/teleprint-me/ccheck.c ccheck
   cd ccheck
   git submodule update --init --recursive --remote
   ```

2. Build the project using CMake:
   ```sh
   cmake -B build -DCMAKE_BUILD_TYPE=Debug
   cmake --build build --config Debug
   ```

## Usage

1. Include `ccheck.h` in your project:
   ```c
   #include "ccheck.h"
   ```

2. Define your test cases:
   ```c
   TEST(test_case_name) {
       // your test logic here
   }
   ```

3. Run your tests:
   ```sh
   ./build/bin/ccheck
   ```

## License

This project is licensed under the AGPL License - see the [LICENSE](LICENSE) file for details.
