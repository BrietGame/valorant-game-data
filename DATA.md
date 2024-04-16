# Récap data

## Une fois la game lancée et synchronisée
``Game was launched: VALORANT 21640``

## Valorant Client Info
[gep_internal note](https://overwolf.github.io/api/live-game-data/supported-games/valorant#gep_internal)

```json
{"info":{"gep_internal":{"version_info":"{"local_version":"157.0.1","public_version":"157.0.1","is_updated":true}"}},"feature":"gep_internal"}
```

## Features
- gep_internal
- me
- game_info
- match_info
- kill
- death

## Game Info
[Game Info Docs](https://overwolf.github.io/api/live-game-data/supported-games/valorant#info-updates-3)
### Scoreboard
- `scoreboard_0` : BrietGame #EUW
- `scoreboard_4` : iNo llaavvii #euw

**Donc le chiffre après l'underscore est l'index du joueur dans la liste des joueurs de la game.**
```json
gameInfo: {
"info": {
"match_info": {
"scoreboard_0": "{\"name\":\"BrietGame #EUW\",\"character\":\"Mage\",\"teammate\":false,\"alive\":true,\"player_id\":\"54f140b6-6278-5c05-85ca-0c86cae73185\",\"shield\":0,\"weapon\":\"TX_Hud_Pistol_Classic\",\"ult_points\":0,\"ult_max\":7,\"kills\":0,\"deaths\":1,\"assists\":0,\"money\":0,\"is_local\":true}"
}
},
"feature": "match_info"
}
```

```json
gameInfo: {
    "info": {
        "match_info": {
            "scoreboard_4": "{\"name\":\"iNo llaavvii #euw\",\"character\":\"Breach\",\"teammate\":false,\"alive\":false,\"player_id\":\"0f2db3b9-0cef-5759-b057-65daeb37fb8e\",\"shield\":2,\"weapon\":\"TX_Hud_Sniper_Operater\",\"ult_points\":0,\"ult_max\":9,\"kills\":4,\"deaths\":2,\"assists\":0,\"money\":0,\"is_local\":false}"
        }
    },
    "feature": "match_info"
}
```