"It's the fish that John West reject that makes John West the best"

Here's where I put rejected PRs that, in my opinion, are superior.

Below is the original unaltered README

# Pattern Language 

![Unit Tests](https://img.shields.io/github/actions/workflow/status/WerWolv/PatternLanguage/tests.yml?branch=master&label=Unit%20Tests&style=flat-square)<br>
<!--
![Coverage Status](https://img.shields.io/coveralls/github/WerWolv/PatternLanguage?style=flat-square&label=Library%20Coverage)
![Coverage Status](https://img.shields.io/coveralls/github/WerWolv/ImHex-Patterns?style=flat-square&label=Pattern%20Coverage)
-->
This repository contains the source code for the Pattern Language used by the [ImHex](https://github.com/WerWolv/ImHex) Hex Editor.

**[Documentation](https://imhex.werwolv.net/docs)**

## Examples

```rust
fn main() {
    std::print("Hello World");
}
```

```cpp
enum Type : u16 {
    A = 0x50,
    B,
    C
};

struct MyStruct {
    Type type;
    u32 x, y, z;
    padding[10];
    double a;
};

MyStruct myStruct @ 0x100;
```

## Standard Library

The Pattern Language comes with its own standard library which can be found in the [ImHex Pattern database](https://github.com/WerWolv/ImHex-Patterns/tree/master/includes/std) 
