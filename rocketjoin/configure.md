# Configure

## Config:

```yaml
#    _____            _        _          _       _
#    |  __ \          | |      | |        | |     (_)
#    | |__) |___   ___| | _____| |_       | | ___  _ _ __
#    |  _  // _ \ / __| |/ / _ \ __|  _   | |/ _ \| | '_ \
#    | | \ \ (_) | (__|   <  __/ |_  | |__| | (_) | | | | |
#    |_|  \_\___/ \___|_|\_\___|\__|  \____/ \___/|_|_| |_|


prefix: "&c&lRocket&e&lJoin &f&l»"
no_permission: "&cYou do not have permission to use this command!"

#Placeholders: {Player} (Name) and {DisplayPlayer} (Display Name)
#PlaceholderAPI Support! Download it from tinyurl.com/PlaceholderAPI

#Join message
enable_join_message: true
join_message: "&a{player} &7joined!"

#Leave message
enable_leave_message: true
leave_message: "&c{player} &7left!"

# ---> VIP <---

# Enable custom features for players with permission "rocketjoin.vip"
enable_vip_features: true

# enable vip custom join.
vip_join: true
# enable vip custom leave.
vip_leave: true
# enable vip sound on join. All players can listen this sound
vip_sound: true
# enable vip join firework.
vip_firework: false
# fireworks to spawn on join. WARNING: IF "vip_firework" IS SET TO false THIS FUNCTION IS DISABLED!
vip_firework_to_spawn: 3


# WARNING: IF "vip_join" IS SET TO false THIS FUNCTION IS DISABLED!
vip_join_message: "&e&l» &6&lVIP &7{player} joined!"
# WARNING: IF "vip_leave" IS SET TO false THIS FUNCTION IS DISABLED!
vip_leave_message: "&e&l» &6&lVIP &7{player} left!"



#⚠(COMING SOON)⚠ Send a title to players that join the server! ⚠(COMING SOON)⚠
#display_title: true
#Join title
#join_title: "&a&lWelcome {player}!"
#Join subtitle
#join_subtitle: "&7Welcome in ServerName Server!"
```

### Join and Leave PlaceholderAPI examples:

```yaml
join_message: "&a{player} &7joined! &7(%vault_prefix%&7)"
leave_message: "&c{player} &7left! &7(%vault_prefix%&7)"
```

### VIP features:

```yaml
vip_sound: true # enable vip sound on join. All players can listen this sound
vip_firework: false #Summon a firework when a vip player join

# Custom join for vip players
vip_join_message: "&e&l» &6&lVIP &7{player} joined!"
# Custom leave for vip players
vip_leave_message: "&e&l» &6&lVIP &7{player} left!"
```

