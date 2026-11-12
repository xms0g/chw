# Cursed Hello World

A ridiculously overengineered Hello, World! written in C, abusing obscure language features, preprocessor tricks, inline assembly, and undefined-behavior-flavored pointer arithmetic to print a string.

Because apparently printf("Hello, World!\n") was too mainstream.
## Features
- Trigraphs — Obscure C preprocessing sequences replace conventional syntax throughout the source.
- K&R C — Old-style function definitions and parameter declarations.
- Preprocessor metaprogramming — Uses parameterized and variadic macros, argument substitution, and conditional compilation to generate declarations and output logic.
- Duff's Device — Eight-way loop unrolling with intentional switch fallthrough.
- Flexible array members — A compiler-extension-based structure initializer for storing the message.
- Pointer arithmetic abuse — Uses commutative array subscripting (a[b] == b[a]) to calculate message length without strlen().
- Bitwise obfuscation — Reconstructs XOR and individual ASCII characters using alternative operations.
- Inline assembly & raw syscalls — Writes directly to stdout without standard library I/O.
- Linker-level chaos — Hides a global variable behind an extern declaration and an intentionally questionable integer conversion.

