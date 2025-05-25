## Admin Commands
| Command                                                     | Permission                          |
|:------------------------------------------------------------|:------------------------------------|
| `/slevels`                                                  | `slevels.command.slevels`           |
| `/slevels addxp <player> <amount>`                          | `slevels.command.addxp`             |
| `/slevels removexp <player> <amount>`                       | `slevels.command.removexp`          |
| `/slevels setxp <player> <amount>`                          | `slevels.command.setxp`             |
| `/slevels addlevel <player> <amount>`                       | `slevels.command.addlevel`          |
| `/slevels removelevel <player> <amount>`                    | `slevels.command.removelevel`       |
| `/slevels setlevel <player> <amount>`                       | `slevels.command.setlevel`          |
| `/slevels addbooster <player> <multiplier> <duration>`      | `slevels.command.addbooster`        |
| `/slevels removebooster <player> <id>`                      | `slevels.command.removebooster`     |
| `/slevels getbooster <player> <id>`                         | `slevels.command.getbooster`        |
| `/slevels getallboosters <player>`                          | `slevels.command.getallboosters.`   |
| `/slevels removeallboosters <player>`                       | `slevels.command.removeallboosters` |
| `/slevels reset <player>`                                   | `slevels.command.reset`             |
| `/slevels reload`                                           | `slevels.command.reload`            |

## Player Commands
| Command                                                     | Permission                          |
|:------------------------------------------------------------|:------------------------------------|
| `/level`                                                    | `slevels.command.level`             |
| `/levelrewards`                                             | `slevels.command.levelrewards`      |

## Placeholders
| Placeholder                                                 | Value                                  |
|:------------------------------------------------------------|:--------------------------------------------|
| `%slevels_level%`                                           | `Returns player's level.`                                                 |
| `%slevels_next_level%`                                      | `Returns player's next level.`                                            |
| `%slevels_xp%`                                              | `Returns player's current XP.`                                            |
| `%slevels_xp_needed%`                                       | `Returns XP needed for the next level.`                                   |
| `%slevels_percentage%`                                      | `Returns progress percentage to next level.`                              |
| `%slevels_boost_multiplier%`                                | `Returns total active XP boost multiplier.`                               |
| `%slevels_progress_bar%`                                    | `Returns a visual XP progress bar.`                                       |
| `%slevels_claimed_REWARD%`                                  | `Returns the status of a reward.`                                         |
| `%slevels_leaderboard_xp_POSITION%`                         | `Returns the data of the player with the most total XP`                   |
| `%slevels_leaderboard_level_POSITION%`                      | `Returns the data of the highest level player`                            |
| `%slevels_leaderboard_position_xp%`                         | `Returns the player's position on the xp leaderboard.`                    |
| `%slevels_leaderboard_position_level%`                      | `Returns the player's position on the level leaderboard.`                 |
| `%slevels_leaderboard_name_xp_POSITION%`                    | `Returns the name of the player with the most xp in that position`        |
| `%slevels_leaderboard_name_level_POSITION%`                 | `Returns the name of the player with the highest level at that position.` |
| `%slevels_leaderboard_amount_xp_POSITION%`                  | `Returns the total XP of the player at that position.`                    |
| `%slevels_leaderboard_amount_level_POSITION%`               | `Returns the level of the player at that position.`                       |
