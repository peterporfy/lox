# Start

## Compile and run repl

- `gcc *.c -o clox && ./clox`

## Run a file

- `./clox ../01.lox`

# Options

`common.h` defines the following options:
- `DEBUG_TRACE_EXECUTION` - print each instruction before executing it
- `DEBUG_PRINT_CODE` - print the bytecode of the compiled code
- `DEBUG_STRESS_GC` - run the garbage collector after every allocation and deallocation
- `DEBUG_LOG_GC` - log garbage collection events
