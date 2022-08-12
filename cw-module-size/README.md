# cw-module-size


`module_size` and `module_size.sh`

Memory profiling of compiled modules. `module_size.sh` executes `module_size`,
and uses valgrind's memory profiling tool (massif) to compute the amount of heap
memory used by a compiled module.

Install using 
cargo install cw-module-size