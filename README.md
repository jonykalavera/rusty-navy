# rusty-navy

#DontJudge

```
struct Player {
  name: String
}
struct Match {
    players: vec<Player>,
    playerInTurn: Player,
    turns: u8
}

enum SlotSate {
    Empty,
    Occupied,
    Destroyed
}

struct Map {
    width: u8,
    height: u8,
    slots: [mut [mut SlotSate.Empty, ..width], ..height],
    ships: vect<Ship>
}

struct Ship {
    size: u8
    health: u16 // Bin
}

fn main() {
    println!("Hello, world!");
}
```
