# rinout

## Intro

(WIP)

cin && cout, but rust version.  

more feature is coming soon(?).  


## Examples

```rust
use rinout::{rout, endl};

fn main() {
    rout << "Hello, world!" << endl;
    rout << "123" << endl;
}
```

Output is:

```txt
Hello, world!
123
```

```rust
use rinout::rin;

fn main() {
  let mut s: String;
  let mut num: i32;
  rin >> s >> num;
}
```

