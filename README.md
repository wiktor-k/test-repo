<div align="center">
  <!-- Crates version -->
  <a href="https://metacode.biz/@wiktor" rel="me">
    <img src="https://img.shields.io/crates/v/pgp.svg?style=flat-square"
    alt="Crates.io version" />
  </a>
</div

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

Raw test:

```rust
fn main() {}
```

With spaces:

```rust file=test.rs id=3 comment=test
fn main() {}
```

With commas:

```rust,file=test.rs,id=3,comment=test
fn main() {}
```

test
