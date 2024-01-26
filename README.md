# Test Repo

```mermaid
    stateDiagram
    [*] --> Active

    state Active {
        [*] --> NumLockOff
        NumLockOff --> NumLockOn : EvNumLockPressed
        NumLockOn --> NumLockOff : EvNumLockPressed
    }
```

Is this OK?

```rust
fn main() {}
```

```rust file=test.rs
fn main() {}
```

```rust,file=test.rs
fn main() {}
```

test
