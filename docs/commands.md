## Admin Commands
| Command                                                     | Permission                          |
|:------------------------------------------------------------|:------------------------------------|
| `/slevels`                                                  | `slevels.command.slevels`           |
| `/slevels addxp <player> <amount>`                          | `slevels.command.addxp`             |
| `/slevels removexp <player> <amount>`                       | `slevels.command.removexp`          |
| `/slevels setxp <player> <amount>`                          | `slevels.command.setxp`             |
| `/slevels addlevel <player> <amount>`                       | `slevels.command.addlevel`          |
| `/slevels removelevel <player> <amount>`                    | `slevels.command.removelevel`       |
| `/slevels setlevel all <player> <amount>`                   | `slevels.command.setlevel`          |
| `/slevels addbooster all <player> <multiplier> <duration>`  | `slevels.command.addbooster`        |
| `/slevels removebooster <player> <id>`                      | `slevels.command.removebooster`     |
| `/slevels getbooster <player> <id>`                         | `slevels.command.getbooster`        |
| `/slevels getallboosters <player>`                          | `slevels.command.getallboosters.`   |
| `/slevels removeallboosters <player>`                       | `slevels.command.removeallboosters` |
| `/slevels reset <player> <id>`                              | `slevels.command.reset`             |

## Player Commands
| Command                                                     | Permission                          |
|:------------------------------------------------------------|:------------------------------------|
| `/level`                                                    | `slevels.command.level`             |
| `/levelrewards`                                             | `slevels.command.levelrewards`      |

## Placeholders
| Placeholder                                                 | Value                                  |
|:------------------------------------------------------------|:--------------------------------------------|
| `%slevels_level%`                                           | `Returns player's level.`                   |
| `%slevels_next_level%`                                      | `Returns player's next level.`              |
| `%slevels_xp%`                                              | `Returns player's current XP.`              |
| `%slevels_xp_needed%`                                       | `Returns XP needed for the next level.`     |
| `%slevels_percentage%`                                      | `Returns progress percentage to next level.`|
| `%slevels_boost_multiplier%`                                | `Returns total active XP boost multiplier.` |
| `%slevels_progress_bar%`                                    | `Returns a visual XP progress bar.`         |
