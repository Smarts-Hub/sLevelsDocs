## Levels Configuration 🃏
- Navigate to the `plugins/sLevels` folder on your server.
- Open the `levels.yml` file with a text editor.
- You will need to define each level and the required experience.

### Example
```yaml
1: 500
2: 750
3: 1000
4: 1500
5: 2500
6: 4000
7: 5000
8: 7500
9: 8500
10: 10000
```

- Save the changes and restart your server to apply the new level configuration.
- Test the levels in-game to ensure they are functioning as expected.

## Language Configuration 📕

- Navigate to the `plugins/sLevels` folder on your server.
- Open the `config.yml` file with a text editor.
- Locate `language` and configure the following settings:

### Example
```yaml
language: en # lang_en.yml ---> en 
```

## Reward Menu Configuration 🎁
- Navigate to the `plugins/sLevels/menus` folder on your server.
- Open the `main.yml` file with a text editor.
- Modify the menu to your liking by changing item names, quantities, or commands.

### Example
```yaml
Title: "&7sLevels &8| &7Rewards"
Size: 54

Paginated:
  Enabled: true
  Next:
    Page: "main.yml" # It will redirect you to the "main.yml" menu
    Material: ARROW
    Name: "&aNext Page"
    Slot: 50
    Lore:
      - "&7Click to go to the next page"

  Previous:
    Page: "main.yml" # It will redirect you to the "main.yml" menu
    Material: ARROW
    Name: "&cPrevious Page"
    Slot: 48
    Lore:
      - "&7Click to go to the previous page"

Items:
  Glass:
    Slot:
      - 45
      - 46
      - 47
      - 51
      - 52
      - 53
    Material: "BLACK_STAINED_GLASS_PANE"
    Name: "&8"
    Glow: false
    Lore: []

  Info:
    Slot: 49
    Material: "BOOK"
    Name: "&bLevel Rewards"
    Glow: true
    Lore:
      - "&7Earn rewards"
      - "&7by leveling up!"

Levels:
  1:
    Slot: 0
    Claim-Actions:
      - "[CONSOLE] eco give %player% 1000"
      - "[GIVE] diamond 1"
      - "[MESSAGE] &aYou have claimed the rewards for Level 1!"
      - "[SOUND] ENTITY_PLAYER_LEVELUP"

    Locked:
      Material: "RED_STAINED_GLASS_PANE"
      Name: "&cLevel 1 (Locked)"
      Lore:
        - ""
        - "&cRewards:"
        - "&7- &e$1000"
        - "&7- &ex1 Diamond"
        - ""
        - "&cYou can't claim this reward yet!"

    Unlocked:
      Material: "LIME_STAINED_GLASS_PANE"
      Name: "&aLevel 1 (Unlocked)"
      Lore:
        - ""
        - "&aRewards:"
        - "&7- &e$1000"
        - "&7- &ex1 Diamond"
        - ""
        - "&aClick to claim!"

    Claimed:
      Material: "GRAY_STAINED_GLASS_PANE"
      Name: "&cLevel 1 (Claimed)"
      Lore:
        - ""
        - "&aRewards:"
        - "&7- &e$1000"
        - "&7- &ex1 Diamond"
        - ""
        - "&aYou have already claimed this reward!"
```

- Save the changes and restart your server to apply the new rewards configuration.
- Test the rewards in-game to ensure they are functioning as expected.
