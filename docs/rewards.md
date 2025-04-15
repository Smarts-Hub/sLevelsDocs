## Claim Actions 🔥

`sLevels` currently includes a total of 5 actions when claiming a reward, which are:

| Action                 | Description                                      | Example                                 |
|:-----------------------|:-------------------------------------------------|:----------------------------------------|
| `[CONSOLE]`            | Run a command from the console.                  | `[CONSOLE] eco give %player% 1000`      |
| `[GIVE]`               | Give an item to the user                         | `[GIVE] diamond 1`                      |
| `[MESSAGE]`            | Send a message to the user                       | `[MESSAGE] &aYou have claimed the rewards for Level 1!`      |
| `[SOUND]`              | Plays a sound to the user                        | `[SOUND] ENTITY_PLAYER_LEVELUP`         |
| `[BOOST]`              | Give the user an XP multiplier                   | `[BOOST] 1.5 2h (s, m, h, d)`           |

## How to Expand 🪐

To expand, you'll just need to create another `.yml` file with the same format, modify what you want, and to make it functional, in the Pagination section, change next/previous page.

### Example
```yaml
Paginated:
  Enabled: true
  Next:
    Page: "next_menu.yml" # It will redirect you to the "next_menu.yml" menu
    Material: ARROW
    Name: "&aNext Page"
    Slot: 50
    Lore:
      - "&7Click to go to the next page"

  Previous:
    Page: "previous_menu.yml" # It will redirect you to the "previous_menu.yml" menu
    Material: ARROW
    Name: "&cPrevious Page"
    Slot: 48
    Lore:
      - "&7Click to go to the previous page"
```