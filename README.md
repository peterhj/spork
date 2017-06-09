# spork

`spork` is an experimental library in Rust for "remote fork"-like functionality
on Linux. The general approach is based on checkpoint-restart.

Process state includes:

- Thread contexts
- Memory
- File descriptors
- Linked shared objects
