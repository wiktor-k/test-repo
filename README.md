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

Flow:

```mermaid
flowchart TD
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
```

Is this OK?

Packet:

```mermaid
---
title: "TCP Packet"
---
packet-beta
  0-15: "Source Port"
  16-31: "Destination Port"
  32-63: "Sequence Number"
  64-95: "Acknowledgment Number"
  96-99: "Data Offset"
  100-105: "Reserved"
  106: "URG"
  107: "ACK"
  108: "PSH"
  109: "RST"
  110: "SYN"
  111: "FIN"
  112-127: "Window"
  128-143: "Checksum"
  144-159: "Urgent Pointer"
  160-191: "(Options and Padding)"
  192-255: "Data (variable length)"

```

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
