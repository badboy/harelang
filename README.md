# The Hare standard library [![builds.sr.ht status](https://builds.sr.ht/~sircmpwn/stdlib.svg)](https://builds.sr.ht/~sircmpwn/stdlib?)

This is the standard library for the [Hare](https://harelang.org) programming
language.

## Hare stdlib mandate

The Hare standard library shall provide:

1. Useful features to compliment Hare language features
2. An interface to the host operating system
3. Implementations of broadly useful algorithms
4. Implementations of broadly useful formats and protocols
5. Introspective meta-features for Hare-aware programs

Each of these services shall:

1. Have a concise and straightforward interface
2. Correctly and completely implement the useful subset of the required behavior*
3. Provide complete documentation for each exported symbol
4. Be sufficiently tested to provide confidence in the implementation

\* This means read the RFC before you start writing the code

Some examples of on-topic features include:

### Language features

- Memory allocation
- High-level string manipulation (e.g. concat, replace, split)
- High-level slice manipulation (e.g. sort)
- Test harness and testing support code

### Introspection

- Hare lexing, parsing (and unparsing), and type checking
- ELF, DWARF
- Stack unwinding

### Operating system interface

- I/O support
- Filesystem access
- Sockets

### Useful algorithms

- Sorting, searching
- Cryptography
- Hashing
- Compression
- Date & time support
- Regex

### Useful formats & protocols

- Internet protocol suite
- JSON, XML, INI, HTML
- tar, zip, cpio
- MIME, RFC 2822
