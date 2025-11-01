# Suit
💼 Simple testing library

# Example
Simple example:

```rust
/// Imports
use suit/test for Test
use suit/run as test_runner
use suit/assert for assert_eq
use std/list for List

/// Simple test `a`
fn test_a() {
    assert_eq(2 + 2, 4);
}

/// Simple test `b`
fn test_b() {
    assert_eq(8 / 4, 2);
}

/// Main function
fn main() {
    let tests = List();
    tests.push(Test(test_a));
    tests.push(Test(test_b));
    test_runner.run(tests);
}
```
