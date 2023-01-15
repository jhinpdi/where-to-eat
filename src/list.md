# Listing

```rust
use rand::Rng;

fn main() {
    let db = vec!["los_carnalitos"];
    let mut rng = rand::thread_rng();
    let rand_idx: u8 = rng.gen();
    println!("{:?}", db.get(rand_idx));
}
```
