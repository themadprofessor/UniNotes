# Programming Paradigms

## Imperative

Programs consist of statements which modify a state i.e. memory.
Examples include:

* C
```c
int x = 41;
x = x + 1;
```
* Rust
```rust
let mut x = 41u64;
x = x + 1;
```

## Structured

Programs consist of predefined structures marked with keywords.
Many languages are structured as well as other paradigms.
Examples include:

* C
```c
int x = 0;
for (int i = 0; i < 20; i++) {
  x += i;
}
```
* Rust
```rust
struct Foo;

trait Bar;

impl Bar for Foo {}
```

## Object Orientated

Programs which encapsulate data and behaviour in objects, defined by classes.
Examples include:

* Java
```java
class Foo {
  int bar = 0;

  void baz() {
    this.bar++;
  }
}
```

## Functional

Programs which are composed of pure functions which do not explicitly modify state.
Examples include:

* Haskell
```haskell
factorial 0 = 1
factorial n = n * factorial(n - 1)
```
