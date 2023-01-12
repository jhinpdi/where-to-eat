# Listing

- Los Carnalitos

```rust
use rand::seq::SliceRandom;

fn main() {
    let db = vec!["los_carnalitos"];
    println!("{:?}", db.choose(&mut rand::thread_rng()));
}
```
