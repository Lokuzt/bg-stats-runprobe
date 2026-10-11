### Combat — `/root/GameRoot/SceneLoader/Combat`

- **Class:** `Node2D`
- **Script:** `res://NodeCombat/Combat.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 8, 9, 10, 11, 12, 13, 17, 18, 19, 22, 23, 24, 25, 28, 29

**Script property values (only changes are listed):**

```json
{
  "_combat_log_restored_for_rewards": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": true
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": true
    }
  ],
  "_defeat_triggered": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "_log_button_home_position": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(0.0, 0.0)"
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "(0.0, 1104.0)"
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(0.0, 0.0)"
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "(0.0, 1104.0)"
    }
  ],
  "_seduced_active": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "_training_combat_ended": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "_training_result_banked": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "card_effect_handler": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Object",
        "value": "<RefCounted#-9223371125549952800>"
      }
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<RefCounted#-9223370201695776205>"
      }
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Object",
        "value": "<RefCounted#-9223369150502530650>"
      }
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Object",
        "value": "<RefCounted#-9223367368309204239>"
      }
    }
  ],
  "card_grid_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "CardGrid",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CardGrid"
      }
    }
  ],
  "card_manager": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "CombatCardManager",
        "path": "/root/GameRoot/SceneLoader/Combat/CombatCardManager"
      }
    }
  ],
  "card_pile_hit_area": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "HBoxContainer",
        "name": "HBoxContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CardPileMargin/HBoxContainer"
      }
    }
  ],
  "card_pile_margin_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "CardPileMargin",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CardPileMargin"
      }
    }
  ],
  "card_target_area": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "CardTargetArea",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CardTargetContainer/CardTargetArea"
      }
    }
  ],
  "card_target_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "CardTargetContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CardTargetContainer"
      }
    }
  ],
  "cards_played_this_turn": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 3
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 0
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 3
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 1
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 3
    }
  ],
  "combat_camera": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Camera2D",
        "name": "Camera2D",
        "path": "/root/GameRoot/SceneLoader/Combat/Camera2D"
      }
    }
  ],
  "combat_hero": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "CombatHero",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/CombatHero"
      }
    }
  ],
  "combat_log_button": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Button",
        "name": "CombatLogButton",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CombatLogButtonMargin/CombatLogButton"
      }
    }
  ],
  "combat_log_button_margin": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "CombatLogButtonMargin",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CombatLogButtonMargin"
      }
    }
  ],
  "combat_log_panel": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "CombatLogPanel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CombatLogPanel"
      }
    }
  ],
  "current_enemy": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "@Node2D@944",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@944"
      }
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "@Node2D@3573",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@3573"
      }
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "@Node2D@6767",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@6767"
      }
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "@Node2D@13154",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@13154"
      }
    }
  ],
  "dev_lose_button": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Button",
        "name": "DevLoseButton",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/DevLoseButton"
      }
    }
  ],
  "dev_win_button": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Button",
        "name": "DevWinButton",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/DevWinButton"
      }
    }
  ],
  "dev_win_button_arousal": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Button",
        "name": "DevWinButtonArousal",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/DevWinButtonArousal"
      }
    }
  ],
  "discard_pile_count": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Label",
        "name": "DiscardPileLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CardPileMargin/HBoxContainer/VBoxContainer/DiscardPileLabel"
      }
    }
  ],
  "draw_pile_count": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Label",
        "name": "DrawPileLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CardPileMargin/HBoxContainer/VBoxContainer/DrawPileLabel"
      }
    }
  ],
  "effect_manager_signal_emitter": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Object",
        "value": "<RefCounted#-9223371125566730017>"
      }
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<RefCounted#-9223370201712554768>"
      }
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Object",
        "value": "<RefCounted#-9223369150519306304>"
      }
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Object",
        "value": "<RefCounted#-9223367368325981727>"
      }
    }
  ],
  "end_turn_button": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "EndTurnButton",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/EndTurnMarginContainer/EndTurnButton"
      }
    }
  ],
  "end_turn_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "EndTurnMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/EndTurnMarginContainer"
      }
    }
  ],
  "enemy_ai_service": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "EnemyContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer"
      }
    }
  ],
  "enemy_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "EnemyContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer"
      }
    }
  ],
  "enemy_node_scene": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Resource",
        "class": "PackedScene",
        "path": "res://Enemy/CombatEnemy.tscn"
      }
    }
  ],
  "enemy_queue": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "_kind": "Node",
          "class": "Node2D",
          "name": "@Node2D@944",
          "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@944"
        }
      ]
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "_kind": "Node",
          "class": "Node2D",
          "name": "@Node2D@3573",
          "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@3573"
        }
      ]
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        {
          "_kind": "Node",
          "class": "Node2D",
          "name": "@Node2D@6767",
          "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@6767"
        }
      ]
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        {
          "_kind": "Node",
          "class": "Node2D",
          "name": "@Node2D@13154",
          "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@13154"
        }
      ]
    }
  ],
  "is_player_turn": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "last_card_played_this_turn": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {}
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "cost": 1.0,
        "description_key": "deal_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 5
          }
        ],
        "id": "lick",
        "name": "Lick",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal"
        ],
        "type": "general",
        "uid": "1791739655-57941-2508166965",
        "upgrade_count": 1,
        "upgrades": [
          {
            "upgrade_id": "limp",
            "upgrade_index": 0
          }
        ]
      }
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {}
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 1.0,
        "description_key": "self_arousal_and_arousal_all_enemies",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 3.0
          },
          {
            "placeholder_id": 2.0,
            "slot": "secondary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "all_enemies"
              ],
              "size": 1
            },
            "value": 11.0
          }
        ],
        "id": "desperation",
        "isImplemented": "true",
        "is_pinned": false,
        "name": "Desperation",
        "rarity": "uncommon",
        "reward_type": "card",
        "sex_type": "anal",
        "sex_type_enum": 2,
        "source_deck": "moira",
        "tags": [
          "arousal",
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-179203-1032050411",
        "upgrade_count": 1,
        "upgrades": []
      }
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "available_in_floors": [],
        "cost": 1.0,
        "description_key": "deal_willpower_and_reduce_enemy_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "WILLPOWER",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": -6.0
          },
          {
            "placeholder_id": 2.0,
            "slot": "secondary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": -2.0
          }
        ],
        "id": "mock",
        "name": "Mock",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "willpower"
        ],
        "type": "general",
        "uid": "1791739655-57941-165729235",
        "upgrade_count": 1,
        "upgrades": []
      }
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 1.0,
        "description_key": "deal_arousal_and_draw_card",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 8.0
          },
          {
            "action_id": "DRAW_CARDS",
            "placeholder_id": 2.0,
            "slot": "primary",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 1.0
          }
        ],
        "id": "perky_pull",
        "name": "Perky Pull",
        "rarity": "uncommon",
        "reward_type": "card",
        "source_deck": "moira",
        "tags": [
          "draw_cards",
          "arousal"
        ],
        "type": "trick",
        "uid": "1791739655-498327-3730739093",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "map_bg_texture": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "MapBG",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/MapBG"
      }
    }
  ],
  "map_fg_sprite": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Sprite2D",
        "name": "MapFG",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/ForegroundParallax/ForeGroundParallaxLayer/MapFG"
      }
    }
  ],
  "map_fog": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Sprite2D",
        "name": "FogSprite2D",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/FogParallax/ParallaxLayerFog/FogSprite2D"
      }
    }
  ],
  "panties_display_rect": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "PantiesDisplayRect",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/CentralImagesLayer/CentralImages/CentralImages/Panties/PantiesDisplayRect"
      }
    }
  ],
  "panties_display_rect2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "PantiesDisplayRect2",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/CentralImagesLayer/CentralImages/CentralImages/Panties/PantiesDisplayRect2"
      }
    }
  ],
  "player_max_hand_size": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 10
    }
  ],
  "position_fade_transition_duration": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0.4
    }
  ],
  "rewards_screen_instance": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Rewards",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards"
      }
    }
  ],
  "screen_center_x": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 960.0
    }
  ],
  "sex_display_rect": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexDisplayRect",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/CentralImagesLayer/CentralImages/CentralImages/SexTypeContainer/SexDisplayRect"
      }
    }
  ],
  "sex_manager": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "SexTypeContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/CentralImagesLayer/CentralImages/CentralImages/SexTypeContainer"
      }
    }
  ],
  "sex_video_player": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "VideoStreamPlayer",
        "name": "SexVideoPlayer",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/CentralImagesLayer/CentralImages/CentralImages/SexTypeContainer/SexVideoHost/SexVideoPlayer"
      }
    }
  ],
  "soak_pile_count": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Label",
        "name": "SoakPileLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/CardPileMargin/HBoxContainer/VBoxContainer/SoakPileLabel"
      }
    }
  ],
  "ui_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "UI_Container",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container"
      }
    }
  ],
  "wip_floor_dialog": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "WipFloorDialog",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/WipFloorDialog"
      }
    }
  ],
  "world_layout": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "UnitContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
_advance_to_floor, _bank_training_result, _clear_combat_refs, _determine_rewards_for_node_type, _end_run_as_victory, _end_training_combat, _execute_end_enemy_turn_action, _execute_end_player_turn_action, _execute_process_end_of_turn_action, _execute_start_enemy_turn_action, _execute_start_player_turn_action, _generate_upgraded_card_rewards, _handle_combat_victory, _hide_card_target_visual, _initialize_player, _on_boss_rewards_completed, _on_card_piles_gui_input, _on_combat_hero_defeated, _on_combat_hero_orgasmed, _on_combat_log_button_pressed, _on_dev_lose_button_pressed, _on_dev_win_button_arousal_pressed, _on_dev_win_button_pressed, _on_rewards_screen_completed, _prompt_enter_wip_floor, _restore_combat_log_for_rewards, _set_combat_background, _shuffle_discard_into_draw, _sync_panties_card_sex_type, _unhandled_input, _update_all_card_highlights_deferred, bank_training_result_on_combat_exit, cancel_card_drag, discard_hand_visuals_to_draw_pile, draw_additional_cards, end_card_drag, get_card_effect_handler, get_card_playability_info, get_combat_position, modify_player_energy, queue_cards_for_creation, retrieve_from_discard, set_hand_interactive, show_card_selection_grid, start_card_drag, start_combat, update_player_energy
```

**Relevant method signatures:**

```json
[
  {
    "args": [],
    "default_args": [],
    "name": "_initialize_player"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "has_panties",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_sync_panties_card_sex_type"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_on_combat_hero_orgasmed"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_on_combat_hero_defeated"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_set_combat_background"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_handle_combat_victory"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "node_type",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_determine_rewards_for_node_type"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "rarity",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_count",
        "type": 2,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades_per_card",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_generate_upgraded_card_rewards"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_on_boss_rewards_completed"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_clear_combat_refs"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_prompt_enter_wip_floor"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_end_run_as_victory"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "next_floor_number",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_advance_to_floor"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_restore_combat_log_for_rewards"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_on_rewards_screen_completed"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_playability_info"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_id",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "count",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "queue_cards_for_creation"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_update_all_card_highlights_deferred"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_shuffle_discard_into_draw"
  },
  {
    "args": [
      {
        "class_name": "Control",
        "hint": 0,
        "hint_string": "",
        "name": "card_ui",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "start_card_drag"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "global_mouse_pos",
        "type": 5,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "end_card_drag"
  },
  {
    "args": [],
    "default_args": [],
    "name": "cancel_card_drag"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_hide_card_target_visual"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "amount",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "modify_player_energy"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "count",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "draw_additional_cards"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "count",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "retrieve_from_discard"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "payload",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_execute_start_player_turn_action"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_execute_end_player_turn_action"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "enemy_uuid",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "cards_played",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_end_training_combat"
  },
  {
    "args": [
      {
        "class_name": "CombatEnemy",
        "hint": 0,
        "hint_string": "",
        "name": "dummy",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "enemy_id",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "cards_played",
        "type": 2,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "ending",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_bank_training_result"
  },
  {
    "args": [
      {
        "class_name": "CombatEnemy",
        "hint": 0,
        "hint_string": "",
        "name": "dummy",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "ending",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "bank_training_result_on_combat_exit"
  },
  {
    "args": [],
    "default_args": [],
    "name": "start_combat"
  },
  {
    "args": [],
    "default_args": [],
    "name": "update_player_energy"
  },
  {
    "args": [],
    "default_args": [],
    "name": "get_combat_position"
  },
  {
    "args": [],
    "default_args": [],
    "name": "get_card_effect_handler"
  },
  {
    "args": [
      {
        "class_name": "InputEvent",
        "hint": 0,
        "hint_string": "",
        "name": "event",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_on_card_piles_gui_input"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "cards",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "max_selections",
        "type": 2,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "title",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [
      "Select Cards"
    ],
    "name": "show_card_selection_grid"
  },
  {
    "args": [],
    "default_args": [],
    "name": "discard_hand_visuals_to_draw_pile"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_on_dev_win_button_pressed"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_on_dev_win_button_arousal_pressed"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_on_combat_log_button_pressed"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_on_dev_lose_button_pressed"
  }
]
```


### RunState — `/root/RunState`

- **Class:** `Node`
- **Script:** `res://Data/State/RunState.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32

**Script property values (only changes are listed):**

```json
{
  "_arousal": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 7
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 17
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 63
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 14
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "_arousal_max": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 100
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": 80
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 100
    }
  ],
  "_cum_value": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 23
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 45
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 89
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 128
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "_willpower": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 100
    },
    {
      "snapshot": 16,
      "timestamp": "2026-10-11T14:30:30",
      "value": 90
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": 103
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 60
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 2
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 100
    }
  ],
  "_willpower_max": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 100
    },
    {
      "snapshot": 16,
      "timestamp": "2026-10-11T14:30:30",
      "value": 103
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 100
    }
  ],
  "active_deal": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    },
    {
      "snapshot": 21,
      "timestamp": "2026-10-11T14:32:39",
      "value": {
        "base_cost": 0,
        "condition_data": {
          "description_key": "gain_anal_creampies_condition",
          "difficulty": 1,
          "removal_condition": "anal_creampies",
          "value": 3
        },
        "condition_description": "Gain [b]3[/b] Anal Creampies. (0 / 3)",
        "condition_key": "gainAnalCreampies",
        "display_cost": 0,
        "id": "special_deal_blindfold",
        "name": "A Risky Deal",
        "negative_data": {
          "description_key": "lazy_deal_description",
          "difficulty": 0,
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "stat_name",
                "value",
                "conditions",
                "targets"
              ],
              "size": 5
            }
          ]
        },
        "negative_description": "At the start of Round [b]1[/b], lose [b]1[/b] Energy.",
        "negative_key": "lazy",
        "rarity": "uncommon",
        "reward_toy": {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "description_key": "blindfold_description",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "stat_name",
                "value_per_level",
                "targets"
              ],
              "size": 4
            }
          ],
          "icon": {
            "_kind": "Resource",
            "class": "CompressedTexture2D",
            "path": "res://Toys/Textures/blindfold.png"
          },
          "id": "blindfold",
          "level": 1,
          "levels": 3.0,
          "rarity": "uncommon",
          "weight": 10.0
        },
        "type": "special_deal"
      }
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {}
    }
  ],
  "arousal": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 7
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 17
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 63
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 14
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "arousal_max": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 100
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": 80
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 100
    }
  ],
  "card_draw": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 5
    }
  ],
  "combat_hero_ref": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": null
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "CombatHero",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/CombatHero"
      }
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": null
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "CombatHero",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/CombatHero"
      }
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": null
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "CombatHero",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/CombatHero"
      }
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": null
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "CombatHero",
        "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/CombatHero"
      }
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": null
    }
  ],
  "completed_event_keys": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    }
  ],
  "cum": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 23
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 45
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 89
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 128
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "current_combat_scene": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": null
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "Combat",
        "path": "/root/GameRoot/SceneLoader/Combat"
      }
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": null
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "Combat",
        "path": "/root/GameRoot/SceneLoader/Combat"
      }
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": null
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "Combat",
        "path": "/root/GameRoot/SceneLoader/Combat"
      }
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": null
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "Node2D",
        "name": "Combat",
        "path": "/root/GameRoot/SceneLoader/Combat"
      }
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": null
    }
  ],
  "current_enemy_ref": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": null
    }
  ],
  "deal_progress": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "anal_creampies": 1,
        "deal_arousal": 172,
        "defeat_enemies": 1,
        "enemy_deal_arousal": 165,
        "enemy_deal_willpower": 100,
        "enemy_reduce_arousal": 4,
        "gain_cum": 44,
        "player_deal_arousal": 175,
        "player_lose_willpower": 43,
        "player_orgasms_required": 3,
        "player_reduce_arousal": 215,
        "survive_rounds": 13,
        "unspent_energy": 0
      }
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {}
    }
  ],
  "effective_arousal_max": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 100
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": 80
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 100
    }
  ],
  "energy_gain": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 3
    }
  ],
  "excluded_toy_ids": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": [
        "gemPlug"
      ]
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": [
        "gemPlug",
        "tuningFork",
        "special_deal_blindfold",
        "ridingCrop"
      ]
    },
    {
      "snapshot": 21,
      "timestamp": "2026-10-11T14:32:39",
      "value": [
        "gemPlug",
        "tuningFork",
        "special_deal_blindfold",
        "ridingCrop",
        "blindfold"
      ]
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": []
    }
  ],
  "has_active_run": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": false
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": true
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": false
    }
  ],
  "in_node": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": false
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": false
    },
    {
      "snapshot": 27,
      "timestamp": "2026-10-11T14:35:35",
      "value": true
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": false
    }
  ],
  "is_gameplay_timer_active": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": false
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": true
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": false
    }
  ],
  "main_menu_intro_finished": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": true
    }
  ],
  "max_panties": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 3
    }
  ],
  "new_game_plus_level": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": 8
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "rng": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {
        "_kind": "Object",
        "value": "<RandomNumberGenerator#-9223371859603487197>"
      }
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": {
        "_kind": "Object",
        "value": "<RandomNumberGenerator#-9223365219164611465>"
      }
    }
  ],
  "run_deck": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 7,
      "timestamp": "2026-10-11T14:28:20",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 13,
      "timestamp": "2026-10-11T14:30:05",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 19,
      "timestamp": "2026-10-11T14:32:11",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "draw_cards",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "action_id",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "read_the_room",
          "name": "Read the Room",
          "rarity": "uncommon",
          "reward_type": "card",
          "source_deck": "moira",
          "tags": [
            "draw_cards"
          ],
          "type": "general",
          "uid": "1791739655-319594-537699929",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 24,
      "timestamp": "2026-10-11T14:35:11",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "draw_cards",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "action_id",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "read_the_room",
          "name": "Read the Room",
          "rarity": "uncommon",
          "reward_type": "card",
          "source_deck": "moira",
          "tags": [
            "draw_cards"
          ],
          "type": "general",
          "uid": "1791739655-319594-537699929",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "deal_arousal_and_draw_card",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "action_id",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "perky_pull",
          "name": "Perky Pull",
          "rarity": "uncommon",
          "reward_type": "card",
          "source_deck": "moira",
          "tags": [
            "draw_cards",
            "arousal"
          ],
          "type": "trick",
          "uid": "1791739655-498327-3730739093",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": []
    }
  ],
  "run_scene_path": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": ""
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": "res://UI/MapOverview/MapOverview.tscn"
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "res://NodeCombat/Combat.tscn"
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": "res://UI/MapOverview/MapOverview.tscn"
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "res://NodeCombat/Combat.tscn"
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": "res://NodeShop/Shop.tscn"
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "res://NodeCombat/Combat.tscn"
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": "res://UI/MapOverview/MapOverview.tscn"
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "res://NodeCombat/Combat.tscn"
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": ""
    }
  ],
  "run_seed": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": 1791739655
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "selected_hero_id": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": "moira"
    }
  ],
  "toys": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    },
    {
      "snapshot": 3,
      "timestamp": "2026-10-11T14:27:50",
      "value": [
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "description_key": "gem_plug_description",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "stat_name",
                "value_per_level",
                "targets"
              ],
              "size": 4
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "action",
                "value_per_level"
              ],
              "size": 3
            }
          ],
          "hero": "moira",
          "icon": {
            "_kind": "Resource",
            "class": "CompressedTexture2D",
            "path": "res://Toys/Textures/gemPlug.png"
          },
          "id": "gemPlug",
          "level": 1,
          "levels": 3.0,
          "rarity": "rare",
          "weight": 10.0
        }
      ]
    },
    {
      "snapshot": 21,
      "timestamp": "2026-10-11T14:32:39",
      "value": [
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "description_key": "gem_plug_description",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "stat_name",
                "value_per_level",
                "targets"
              ],
              "size": 4
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "action",
                "value_per_level"
              ],
              "size": 3
            }
          ],
          "hero": "moira",
          "icon": {
            "_kind": "Resource",
            "class": "CompressedTexture2D",
            "path": "res://Toys/Textures/gemPlug.png"
          },
          "id": "gemPlug",
          "level": 1,
          "levels": 3.0,
          "rarity": "rare",
          "weight": 10.0
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "description_key": "blindfold_description",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "stat_name",
                "value_per_level",
                "targets"
              ],
              "size": 4
            }
          ],
          "icon": {
            "_kind": "Resource",
            "class": "CompressedTexture2D",
            "path": "res://Toys/Textures/blindfold.png"
          },
          "id": "blindfold",
          "level": 1,
          "levels": 3.0,
          "rarity": "uncommon",
          "weight": 10.0
        }
      ]
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": [
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "description_key": "gem_plug_description",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "stat_name",
                "value_per_level",
                "targets"
              ],
              "size": 4
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "action",
                "value_per_level"
              ],
              "size": 3
            }
          ],
          "hero": "moira",
          "icon": {
            "_kind": "Resource",
            "class": "CompressedTexture2D",
            "path": "res://Toys/Textures/gemPlug.png"
          },
          "id": "gemPlug",
          "level": 1,
          "levels": 3.0,
          "rarity": "rare",
          "weight": 10.0
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "description_key": "blindfold_description",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "trigger",
                "stat_name",
                "value_per_level",
                "targets"
              ],
              "size": 4
            }
          ],
          "icon": {
            "_kind": "Resource",
            "class": "CompressedTexture2D",
            "path": "res://Toys/Textures/blindfold.png"
          },
          "id": "blindfold",
          "level": 2,
          "levels": 3.0,
          "rarity": "uncommon",
          "weight": 10.0
        }
      ]
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": []
    }
  ],
  "willpower": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 100
    },
    {
      "snapshot": 16,
      "timestamp": "2026-10-11T14:30:30",
      "value": 90
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": 103
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 60
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 2
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 100
    }
  ],
  "willpower_max": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 100
    },
    {
      "snapshot": 16,
      "timestamp": "2026-10-11T14:30:30",
      "value": 103
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 100
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
_apply_lucky_dip_upgrades, _apply_modifier_level_bonus, _find_run_card_index, _gen_card_uid, _set_card_uid, add_card_to_run_deck, apply_upgrade_to_card, can_generate_event, check_deal_completion_on_combat_end, create_combat_card, get_card_instance_by_uid, get_event_usage_count, get_player_toy_ids, get_run_deck_card_by_uid, increment_event_usage, modify_player_stat, prepare_for_map_view, remove_cards_from_run_deck, start_new_run, upgrade_toy
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "run_seed_value",
        "type": 2,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "hero_id",
        "type": 0,
        "usage": 131072
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "ng_level",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "start_new_run"
  },
  {
    "args": [],
    "default_args": [],
    "name": "prepare_for_map_view"
  },
  {
    "args": [
      {
        "class_name": "res://Scripts/GlobalEnums.gd.StatId",
        "hint": 0,
        "hint_string": "",
        "name": "stat_id",
        "type": 2,
        "usage": 65536
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "amount",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "modify_player_stat"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "event_key",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "increment_event_usage"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "event_key",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_event_usage_count"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "event_key",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "can_generate_event"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "toy_instance",
        "type": 27,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "mod_data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_modifier_level_bonus"
  },
  {
    "args": [],
    "default_args": [],
    "name": "get_player_toy_ids"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_uids",
        "type": 28,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "remove_cards_from_run_deck"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_ref",
        "type": 0,
        "usage": 131072
      }
    ],
    "default_args": [],
    "name": "add_card_to_run_deck"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_instance_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_run_deck_card_by_uid"
  },
  {
    "args": [],
    "default_args": [],
    "name": "_gen_card_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_id",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "origin",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [
      null,
      null
    ],
    "name": "_set_card_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_id",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "origin",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [
      null
    ],
    "name": "create_combat_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_lucky_dip_upgrades"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_find_run_card_index"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "apply_upgrade_to_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "toy_to_upgrade",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "upgrade_toy"
  },
  {
    "args": [],
    "default_args": [],
    "name": "check_deal_completion_on_combat_end"
  }
]
```

**Signals:**

```text
cum_changed, deal_completed, map_details_updated, stats_changed, toy_charge_updated
```


### CardDisplay — `/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 5, 6

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": ""
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "cost": 1.0,
        "description_key": "deal_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 7.0
          }
        ],
        "id": "lick",
        "name": "Lick",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal"
        ],
        "type": "general",
        "uid": "1791739655-57941-3941135162",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "lick"
    }
  ],
  "card_image": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "Lick"
    }
  ],
  "card_uid": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-3941135162"
    }
  ],
  "character_border": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 7.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-3941135162"
    }
  ],
  "initial_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.4, 0.4)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 100
    }
  ],
  "scaler": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        "arousal"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_0/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 5, 6

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": ""
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "available_in_floors": [],
        "cost": 1.0,
        "description_key": "deal_willpower_and_reduce_enemy_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "WILLPOWER",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": -6.0
          },
          {
            "placeholder_id": 2.0,
            "slot": "secondary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": -2.0
          }
        ],
        "id": "mock",
        "name": "Mock",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "willpower"
        ],
        "type": "general",
        "uid": "1791739655-57941-165729235",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "mock"
    }
  ],
  "card_image": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "Mock"
    }
  ],
  "card_uid": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-165729235"
    }
  ],
  "character_border": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        {
          "duration": 0,
          "stat_name": "WILLPOWER",
          "targets": [
            "enemy"
          ],
          "value": -6.0
        },
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": -2.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371308136393837> (bound to CardDisplay)"
      }
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-165729235"
    }
  ],
  "initial_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.4, 0.4)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 100
    }
  ],
  "scaler": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        "willpower"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_1/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 5, 6

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": ""
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "cost": 1.0,
        "description_key": "reduce_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": -5.0
          }
        ],
        "id": "sitting_pretty",
        "rarity": "common",
        "sex_type": "versatile",
        "sex_type_change": 1.0,
        "source_deck": "moira",
        "tags": [
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-57941-2477156348",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "sitting_pretty"
    }
  ],
  "card_image": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "Sitting Pretty"
    }
  ],
  "card_uid": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-2477156348"
    }
  ],
  "character_border": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": -5.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-2477156348"
    }
  ],
  "initial_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.4, 0.4)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 100
    }
  ],
  "scaler": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "versatile"
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_2/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 5, 6

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": ""
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "available_in_floors": [],
        "cost": 1.0,
        "description_key": "chance_deal_arousal_or_deal_arousal",
        "effects": [
          {
            "chance": 0.4,
            "luck_proc": true,
            "on_luck_fail": {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 4
            },
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 9.0
          }
        ],
        "id": "feeler",
        "name": "Feeler",
        "rarity": "common",
        "sex_type": "versatile",
        "source_deck": "moira",
        "tags": [
          "arousal",
          "luck"
        ],
        "type": "general",
        "uid": "1791739655-57941-1954779341",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "feeler"
    }
  ],
  "card_image": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "Feeler"
    }
  ],
  "card_uid": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-1954779341"
    }
  ],
  "character_border": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 9.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-1954779341"
    }
  ],
  "initial_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.4, 0.4)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 100
    }
  ],
  "scaler": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "versatile"
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        "arousal",
        "luck"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_3/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 5, 6

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": ""
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    },
    {
      "snapshot": 6,
      "timestamp": "2026-10-11T14:28:17",
      "value": true
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Callable",
        "value": "<anonymous lambda>(self lambda)"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {}
    },
    {
      "snapshot": 6,
      "timestamp": "2026-10-11T14:28:17",
      "value": {
        "available_in_floors": [],
        "cost": 2.0,
        "description_key": "deal_arousal_and_chance_status",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 12.0
          },
          {
            "chance": 0.45,
            "luck_proc": true,
            "placeholder_id": 2.0,
            "slot": "chance",
            "stat_name": "HORNY",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 2.0
          }
        ],
        "id": "daring_display",
        "name": "Daring Display",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal",
          "horny"
        ],
        "type": "luck",
        "uid": "1791739655-57941-4273409655",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "available_in_floors": [],
        "cost": 2.0,
        "description_key": "deal_arousal_and_chance_status",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 12.0
          },
          {
            "chance": 0.45,
            "luck_proc": true,
            "placeholder_id": 2.0,
            "slot": "chance",
            "stat_name": "HORNY",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 2.0
          }
        ],
        "id": "daring_display",
        "name": "Daring Display",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal",
          "horny"
        ],
        "type": "luck",
        "uid": "1791739655-57941-4273409655",
        "upgrade_count": 1,
        "upgrades": []
      }
    },
    {
      "snapshot": 6,
      "timestamp": "2026-10-11T14:28:17",
      "value": {
        "available_in_floors": [],
        "cost": 2.0,
        "description_key": "deal_arousal_and_chance_status",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 12.0
          },
          {
            "chance": 0.45,
            "luck_proc": true,
            "placeholder_id": 2.0,
            "slot": "chance",
            "stat_name": "HORNY",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 2.0
          }
        ],
        "id": "daring_display",
        "name": "Daring Display",
        "rarity": "common",
        "repeat": 1,
        "source_deck": "moira",
        "tags": [
          "arousal",
          "horny",
          "soak"
        ],
        "type": "luck",
        "uid": "1791739655-57941-4273409655",
        "upgrade_count": 1,
        "upgrade_descriptions": [
          {
            "key": "upgrade_echo_description",
            "upgrade_id": "echo"
          }
        ],
        "upgrades": [
          {
            "upgrade_id": "echo",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "daring_display"
    }
  ],
  "card_image": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "Daring Display"
    }
  ],
  "card_uid": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-4273409655"
    }
  ],
  "character_border": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 2
    }
  ],
  "created_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 12.0
        },
        {
          "duration": 0,
          "stat_name": "HORNY",
          "targets": [
            "enemy"
          ],
          "value": 2.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371279027924144> (bound to CardDisplay)"
      }
    },
    {
      "snapshot": 6,
      "timestamp": "2026-10-11T14:28:17",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371251764948138> (bound to CardDisplay)"
      }
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    },
    {
      "snapshot": 6,
      "timestamp": "2026-10-11T14:28:17",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "CardEffect",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/EffectsListCanvasLayer/CardEffect"
      }
    }
  ],
  "energy_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371279061478577> (bound to CardDisplay)"
      }
    },
    {
      "snapshot": 6,
      "timestamp": "2026-10-11T14:28:17",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371248745049223> (bound to CardDisplay)"
      }
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "1791739655-57941-4273409655"
    }
  ],
  "initial_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": false
    },
    {
      "snapshot": 6,
      "timestamp": "2026-10-11T14:28:17",
      "value": true
    }
  ],
  "name_label": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    },
    {
      "snapshot": 6,
      "timestamp": "2026-10-11T14:28:17",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371251597175947> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": "(0.4, 0.4)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": 100
    }
  ],
  "scaler": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": [
        "arousal",
        "horny"
      ]
    },
    {
      "snapshot": 6,
      "timestamp": "2026-10-11T14:28:17",
      "value": [
        "arousal",
        "horny",
        "soak"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 5,
      "timestamp": "2026-10-11T14:28:14",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/MapOverview/CanvasLayer/NewRunBonusSelection/Rewards/UpgradeChoiceOverlay/CardGrid/MainMargin/VerticalLayout/CardScroll/MarginContainer/CardsDisplayGrid/CardWrapper_4/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CombatState — `/root/CombatState`

- **Class:** `Node`
- **Script:** `res://Data/State/CombatState.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32

**Script property values (only changes are listed):**

```json
{
  "activated_toys": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    }
  ],
  "active_enemy_queue": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "_kind": "Node",
          "class": "Node2D",
          "name": "@Node2D@944",
          "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@944"
        }
      ]
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": []
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "_kind": "Node",
          "class": "Node2D",
          "name": "@Node2D@3573",
          "path": "/root/GameRoot/SceneLoader/Combat/WorldCanvasLayer/UnitContainer/EnemyContainer/@Node2D@3573"
        }
      ]
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": []
    }
  ],
  "bait_sources_pending": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    }
  ],
  "baited_card_uids": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    }
  ],
  "chance_rerolls_available": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    }
  ],
  "combat_arousal_damage_dealt": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 96
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": 0
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 114
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": 0
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 172
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": 0
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 211
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "combat_arousal_damage_taken": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 15
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": 0
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 46
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": 0
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 199
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": 0
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 204
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "combat_card_stats": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "1791739655-57941-165729235": {
          "arousal_damage": 0,
          "base_id": "mock",
          "play_count": 1,
          "willpower_damage": 6
        },
        "1791739655-57941-1954779341": {
          "arousal_damage": 29,
          "base_id": "feeler",
          "play_count": 3,
          "willpower_damage": 13
        },
        "1791739655-57941-2477156348": {
          "arousal_damage": 0,
          "base_id": "sitting_pretty",
          "play_count": 1,
          "willpower_damage": 0
        },
        "1791739655-57941-2508166965": {
          "arousal_damage": 11,
          "base_id": "lick",
          "play_count": 3,
          "willpower_damage": 20
        },
        "1791739655-57941-3431250436": {
          "arousal_damage": 0,
          "base_id": "sitting_pretty",
          "play_count": 1,
          "willpower_damage": 0
        },
        "1791739655-57941-3508887784": {
          "arousal_damage": 11,
          "base_id": "lick",
          "play_count": 2,
          "willpower_damage": 9
        },
        "1791739655-57941-3941135162": {
          "arousal_damage": 14,
          "base_id": "lick",
          "play_count": 2,
          "willpower_damage": 11
        },
        "1791739655-57941-4273409655": {
          "arousal_damage": 31,
          "base_id": "daring_display",
          "play_count": 1,
          "willpower_damage": 0
        }
      }
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": {}
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "1791739655-179203-1032050411": {
          "arousal_damage": 12,
          "base_id": "desperation",
          "play_count": 3,
          "willpower_damage": 34
        },
        "1791739655-57941-165729235": {
          "arousal_damage": 0,
          "base_id": "mock",
          "play_count": 1,
          "willpower_damage": 6
        },
        "1791739655-57941-1954779341": {
          "arousal_damage": 25,
          "base_id": "feeler",
          "play_count": 3,
          "willpower_damage": 13
        },
        "1791739655-57941-2508166965": {
          "arousal_damage": 11,
          "base_id": "lick",
          "play_count": 2,
          "willpower_damage": 8
        },
        "1791739655-57941-3508887784": {
          "arousal_damage": 13,
          "base_id": "lick",
          "play_count": 2,
          "willpower_damage": 8
        },
        "1791739655-57941-3941135162": {
          "arousal_damage": 22,
          "base_id": "lick",
          "play_count": 2,
          "willpower_damage": 0
        },
        "1791739655-57941-4273409655": {
          "arousal_damage": 31,
          "base_id": "daring_display",
          "play_count": 1,
          "willpower_damage": 0
        }
      }
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": {}
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "1791739655-179203-1032050411": {
          "arousal_damage": 26,
          "base_id": "desperation",
          "play_count": 5,
          "willpower_damage": 45
        },
        "1791739655-319594-537699929": {
          "arousal_damage": 0,
          "base_id": "read_the_room",
          "play_count": 2,
          "willpower_damage": 0
        },
        "1791739655-57941-165729235": {
          "arousal_damage": 0,
          "base_id": "mock",
          "play_count": 4,
          "willpower_damage": 24
        },
        "1791739655-57941-1954779341": {
          "arousal_damage": 48,
          "base_id": "feeler",
          "play_count": 5,
          "willpower_damage": 0
        },
        "1791739655-57941-2477156348": {
          "arousal_damage": 0,
          "base_id": "sitting_pretty",
          "play_count": 2,
          "willpower_damage": 0
        },
        "1791739655-57941-2508166965": {
          "arousal_damage": 13,
          "base_id": "lick",
          "play_count": 4,
          "willpower_damage": 16
        },
        "1791739655-57941-3431250436": {
          "arousal_damage": 0,
          "base_id": "sitting_pretty",
          "play_count": 2,
          "willpower_damage": 0
        },
        "1791739655-57941-3508887784": {
          "arousal_damage": 16,
          "base_id": "lick",
          "play_count": 3,
          "willpower_damage": 9
        },
        "1791739655-57941-3941135162": {
          "arousal_damage": 38,
          "base_id": "lick",
          "play_count": 5,
          "willpower_damage": 9
        },
        "1791739655-57941-4078609272": {
          "arousal_damage": 0,
          "base_id": "deep_breath",
          "play_count": 2,
          "willpower_damage": 0
        },
        "1791739655-57941-4273409655": {
          "arousal_damage": 31,
          "base_id": "daring_display",
          "play_count": 1,
          "willpower_damage": 0
        }
      }
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": {}
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "1791739655-179203-1032050411": {
          "arousal_damage": 44,
          "base_id": "desperation",
          "play_count": 4,
          "willpower_damage": 13
        },
        "1791739655-319594-537699929": {
          "arousal_damage": 0,
          "base_id": "read_the_room",
          "play_count": 1,
          "willpower_damage": 0
        },
        "1791739655-498327-3730739093": {
          "arousal_damage": 53,
          "base_id": "perky_pull",
          "play_count": 7,
          "willpower_damage": 30
        },
        "1791739655-57941-165729235": {
          "arousal_damage": 0,
          "base_id": "mock",
          "play_count": 2,
          "willpower_damage": 12
        },
        "1791739655-57941-1954779341": {
          "arousal_damage": 40,
          "base_id": "feeler",
          "play_count": 6,
          "willpower_damage": 25
        },
        "1791739655-57941-2477156348": {
          "arousal_damage": 0,
          "base_id": "sitting_pretty",
          "play_count": 4,
          "willpower_damage": 0
        },
        "1791739655-57941-2508166965": {
          "arousal_damage": 6,
          "base_id": "lick",
          "play_count": 3,
          "willpower_damage": 16
        },
        "1791739655-57941-3431250436": {
          "arousal_damage": 0,
          "base_id": "sitting_pretty",
          "play_count": 4,
          "willpower_damage": 0
        },
        "1791739655-57941-3508887784": {
          "arousal_damage": 25,
          "base_id": "lick",
          "play_count": 5,
          "willpower_damage": 9
        },
        "1791739655-57941-3941135162": {
          "arousal_damage": 17,
          "base_id": "lick",
          "play_count": 3,
          "willpower_damage": 10
        },
        "1791739655-57941-4273409655": {
          "arousal_damage": 26,
          "base_id": "daring_display",
          "play_count": 1,
          "willpower_damage": 0
        }
      }
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": {}
    }
  ],
  "combat_charge_tracker": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "8": 0,
        "cards_played_this_turn": 0,
        "current_round": 1
      }
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "8": 0,
        "cards_played_in_combat": 14,
        "cards_played_this_turn": 3,
        "current_round": 5,
        "non_kink_cards_played_in_combat": 14
      }
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": {}
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "8": 0,
        "cards_played_this_turn": 0,
        "current_round": 1
      }
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "8": 0,
        "cards_played_in_combat": 14,
        "cards_played_this_turn": 3,
        "current_round": 5,
        "non_kink_cards_played_in_combat": 14
      }
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": {}
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "8": 0,
        "cards_played_in_combat": 35,
        "cards_played_this_turn": 1,
        "current_round": 13,
        "non_kink_cards_played_in_combat": 35
      }
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": {}
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "8": 0,
        "cards_played_in_combat": 40,
        "cards_played_this_turn": 3,
        "current_round": 14,
        "non_kink_cards_played_in_combat": 40
      }
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": {}
    }
  ],
  "combat_cockwork_bursts": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    }
  ],
  "combat_cum_gained": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 23
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": 0
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 22
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": 0
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 44
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": 0
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 39
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "combat_cum_spent": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    }
  ],
  "combat_deck": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": []
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": []
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "draw_cards",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "action_id",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "read_the_room",
          "name": "Read the Room",
          "rarity": "uncommon",
          "reward_type": "card",
          "source_deck": "moira",
          "tags": [
            "draw_cards"
          ],
          "type": "general",
          "uid": "1791739655-319594-537699929",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": []
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "draw_cards",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "action_id",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "read_the_room",
          "name": "Read the Room",
          "rarity": "uncommon",
          "reward_type": "card",
          "source_deck": "moira",
          "tags": [
            "draw_cards"
          ],
          "type": "general",
          "uid": "1791739655-319594-537699929",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "deal_arousal_and_draw_card",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "action_id",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "perky_pull",
          "name": "Perky Pull",
          "rarity": "uncommon",
          "reward_type": "card",
          "source_deck": "moira",
          "tags": [
            "draw_cards",
            "arousal"
          ],
          "type": "trick",
          "uid": "1791739655-498327-3730739093",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": []
    }
  ],
  "combat_discard_pile": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": [
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "is_pinned": false,
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": []
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": [
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "is_pinned": false,
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "is_pinned": false,
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": []
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "is_pinned": false,
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "is_pinned": false,
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": []
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "is_pinned": false,
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "is_pinned": false,
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "deal_arousal_and_draw_card",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "action_id",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "perky_pull",
          "name": "Perky Pull",
          "rarity": "uncommon",
          "reward_type": "card",
          "source_deck": "moira",
          "tags": [
            "draw_cards",
            "arousal"
          ],
          "type": "trick",
          "uid": "1791739655-498327-3730739093",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": []
    }
  ],
  "combat_dodge_instances_used": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    }
  ],
  "combat_draw_pile": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": [
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "is_pinned": false,
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": []
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": [
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-3431250436",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": []
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3508887784",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "is_pinned": false,
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "draw_cards",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "action_id",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "read_the_room",
          "name": "Read the Room",
          "rarity": "uncommon",
          "reward_type": "card",
          "source_deck": "moira",
          "tags": [
            "draw_cards"
          ],
          "type": "general",
          "uid": "1791739655-319594-537699929",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": []
    }
  ],
  "combat_effects": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "enemy_911908803441": [],
        "player": [
          {
            "applied_round": 1,
            "duration": 0,
            "id": 17,
            "stacks": 1,
            "turns_remaining": 0
          },
          {
            "applied_round": 1,
            "duration": 0,
            "id": 1,
            "stacks": 3,
            "turns_remaining": 0
          }
        ]
      }
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "player": [
          {
            "applied_round": 1,
            "duration": 0,
            "id": 17,
            "stacks": 4,
            "turns_remaining": 0
          },
          {
            "applied_round": 2,
            "duration": 0,
            "id": 10,
            "stacks": 2,
            "turns_remaining": 0
          },
          {
            "applied_round": 3,
            "duration": 0,
            "id": 18,
            "stacks": 2,
            "turns_remaining": 0
          }
        ]
      }
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": {}
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "enemy_1835746202902": [],
        "player": [
          {
            "applied_round": 1,
            "duration": 0,
            "id": 17,
            "stacks": 1,
            "turns_remaining": 0
          },
          {
            "applied_round": 1,
            "duration": 0,
            "id": 1,
            "stacks": 3,
            "turns_remaining": 0
          }
        ]
      }
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "player": [
          {
            "applied_round": 1,
            "duration": 0,
            "id": 17,
            "stacks": 5,
            "turns_remaining": 0
          },
          {
            "applied_round": 1,
            "duration": 0,
            "id": 18,
            "stacks": 1,
            "turns_remaining": 0
          },
          {
            "applied_round": 4,
            "duration": 3,
            "id": 8,
            "stacks": 1,
            "turns_remaining": 2
          }
        ]
      }
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": {}
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "player": [
          {
            "applied_round": 1,
            "duration": 0,
            "id": 17,
            "stacks": 1,
            "turns_remaining": 0
          },
          {
            "applied_round": 2,
            "duration": 0,
            "id": 0,
            "stacks": 2,
            "turns_remaining": 0
          },
          {
            "applied_round": 10,
            "duration": 0,
            "id": 18,
            "stacks": 2,
            "turns_remaining": 0
          },
          {
            "applied_round": 12,
            "duration": 2,
            "id": 11,
            "stacks": 1,
            "turns_remaining": 1
          }
        ]
      }
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": {}
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "player": [
          {
            "applied_round": 1,
            "duration": 0,
            "id": 17,
            "stacks": 1,
            "turns_remaining": 0
          },
          {
            "applied_round": 7,
            "duration": 0,
            "id": 0,
            "stacks": 2,
            "turns_remaining": 0
          },
          {
            "applied_round": 11,
            "duration": 0,
            "id": 18,
            "stacks": 2,
            "turns_remaining": 0
          },
          {
            "applied_round": 14,
            "duration": 0,
            "id": 6,
            "stacks": 2,
            "turns_remaining": 0
          }
        ]
      }
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": {}
    }
  ],
  "combat_enemy_id": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": "incubus"
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "slime"
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": ""
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "dark_elf_man"
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": ""
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "corrupted_knight"
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": ""
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "corrupted_knight"
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": ""
    }
  ],
  "combat_enemy_orgasms_by_type": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "body": 2
      }
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": {}
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "body": 1,
        "pussy": 1
      }
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": {}
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "anal": 1,
        "body": 1
      }
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": {}
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "anal": 2,
        "body": 1
      }
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": {}
    }
  ],
  "combat_enemy_stats": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "corrupted_knight": {
          "defeats": 0,
          "losses": 0,
          "willpower_taken": 34
        }
      }
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": {}
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "corrupted_knight": {
          "defeats": 0,
          "losses": 0,
          "willpower_taken": 58
        }
      }
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": {}
    }
  ],
  "combat_energy": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 3
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 0
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 3
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 0
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 2
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": 0
    }
  ],
  "combat_hand": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": [
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "is_pinned": false,
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": []
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "slot",
                "stat_name",
                "value",
                "targets"
              ],
              "size": 4
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-4078609272",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "deep_breath",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-487113934",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": [
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-3941135162",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": []
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "chance_deal_arousal_or_deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id",
                "on_luck_fail"
              ],
              "size": 8
            }
          ],
          "id": "feeler",
          "is_pinned": false,
          "name": "Feeler",
          "rarity": "common",
          "sex_type": "versatile",
          "source_deck": "moira",
          "tags": [
            "arousal",
            "luck"
          ],
          "type": "general",
          "uid": "1791739655-57941-1954779341",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "reduce_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "sitting_pretty",
          "is_pinned": false,
          "rarity": "common",
          "sex_type": "versatile",
          "sex_type_change": 1.0,
          "source_deck": "moira",
          "tags": [
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-57941-2477156348",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "cost": 1.0,
          "description_key": "deal_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "lick",
          "name": "Lick",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "arousal"
          ],
          "type": "general",
          "uid": "1791739655-57941-2508166965",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        },
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "draw_cards",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "action_id",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "read_the_room",
          "name": "Read the Room",
          "rarity": "uncommon",
          "reward_type": "card",
          "source_deck": "moira",
          "tags": [
            "draw_cards"
          ],
          "type": "general",
          "uid": "1791739655-319594-537699929",
          "upgrade_count": 1,
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": []
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        {
          "available_in_floors": [
            1.0,
            2.0,
            3.0
          ],
          "cost": 1.0,
          "description_key": "self_arousal_and_arousal_all_enemies",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "desperation",
          "isImplemented": "true",
          "is_pinned": false,
          "name": "Desperation",
          "rarity": "uncommon",
          "reward_type": "card",
          "sex_type": "anal",
          "sex_type_enum": 2,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "arousal_reduction"
          ],
          "type": "general",
          "uid": "1791739655-179203-1032050411",
          "upgrade_count": 1,
          "upgrades": []
        },
        {
          "available_in_floors": [],
          "cost": 1.0,
          "description_key": "deal_willpower_and_reduce_enemy_arousal",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            }
          ],
          "id": "mock",
          "name": "Mock",
          "rarity": "common",
          "source_deck": "moira",
          "tags": [
            "willpower"
          ],
          "type": "general",
          "uid": "1791739655-57941-165729235",
          "upgrade_count": 1,
          "upgrades": []
        }
      ]
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": []
    }
  ],
  "combat_max_entangled_stacks": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    }
  ],
  "combat_player_orgasms": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 3
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": 0
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 2
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "combat_soak_pile": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": [
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": []
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": [
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": []
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": []
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        {
          "available_in_floors": [],
          "cost": 2.0,
          "description_key": "deal_arousal_and_chance_status",
          "effects": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 5
            },
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "slot",
                "value",
                "targets",
                "chance",
                "luck_proc",
                "placeholder_id"
              ],
              "size": 7
            }
          ],
          "id": "daring_display",
          "name": "Daring Display",
          "rarity": "common",
          "repeat": 1,
          "source_deck": "moira",
          "tags": [
            "arousal",
            "horny",
            "soak"
          ],
          "type": "luck",
          "uid": "1791739655-57941-4273409655",
          "upgrade_count": 1,
          "upgrade_descriptions": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "key",
                "upgrade_id"
              ],
              "size": 2
            }
          ],
          "upgrades": [
            {
              "_kind": "Dictionary",
              "keys_sample": [
                "upgrade_index",
                "upgrade_id"
              ],
              "size": 2
            }
          ]
        }
      ]
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": []
    }
  ],
  "combat_willpower_damage_dealt": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 59
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": 0
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 69
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": 0
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 103
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": 0
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 115
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "combat_willpower_damage_taken": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 41
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": 0
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 58
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 0
    }
  ],
  "current_round": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 1
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 5
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": 1
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 5
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": 1
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 13
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": 1
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 14
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": 1
    }
  ],
  "enemy_damage_taken_this_round": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {}
    }
  ],
  "enemy_orgasmed_this_turn": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": false
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": true
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "enemy_turn_effects_processed_this_round": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": false
    }
  ],
  "first_attack_used": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": false
    }
  ],
  "instant_cards_to_play": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    }
  ],
  "is_event_combat": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": false
    }
  ],
  "last_sex_source_id": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": ""
    }
  ],
  "last_sex_texture_key": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": ""
    }
  ],
  "luck_procs_this_turn": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 1
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    }
  ],
  "lucky_stacks_at_turn_start": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 1
    },
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 4
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 1
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 4
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 1
    }
  ],
  "pending_extra_enemy_ids": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": []
    }
  ],
  "player_orgasmed_this_turn": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": false
    }
  ],
  "player_turn_effects_processed_this_round": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": false
    },
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    },
    {
      "snapshot": 14,
      "timestamp": "2026-10-11T14:30:26",
      "value": false
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    },
    {
      "snapshot": 20,
      "timestamp": "2026-10-11T14:32:33",
      "value": false
    },
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": true
    },
    {
      "snapshot": 26,
      "timestamp": "2026-10-11T14:35:21",
      "value": false
    },
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": true
    },
    {
      "snapshot": 30,
      "timestamp": "2026-10-11T14:39:32",
      "value": false
    }
  ],
  "sex_balance_stacks": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": {
        "anal": 0,
        "pussy": 0
      }
    }
  ],
  "sex_depth": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    }
  ],
  "sex_engaged_enemy_uuid": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": ""
    }
  ],
  "sex_engagement": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    }
  ],
  "sex_type": [
    {
      "snapshot": 1,
      "timestamp": "2026-10-11T14:27:23",
      "value": 0
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
_ensure_card_stats_entry, advance_round, combat_get_total_enemy_orgasms, get_combat_charge, get_pending_bait_uids, increment_cards_played_in_combat, increment_non_kink_cards_played_in_combat, is_card_bait_blocked, set_combat_charge, shuffle_deck, start_combat, stat_key_for_card, track_card_played, track_damage_dealt_by_card, upgrade_ids_of
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_enemy_id",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 31,
        "hint_string": "String",
        "name": "p_extra_enemy_ids",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 31,
        "hint_string": "Dictionary",
        "name": "initial_effects",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_is_event_combat",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [
      false
    ],
    "name": "start_combat"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "is_card_bait_blocked"
  },
  {
    "args": [],
    "default_args": [],
    "name": "combat_get_total_enemy_orgasms"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "stat_key_for_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "upgrade_ids_of"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "key",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_ensure_card_stats_entry"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "track_card_played"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "card_data",
        "type": 27,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "damage_type",
        "type": 4,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "amount",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "track_damage_dealt_by_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "charge_id",
        "type": 0,
        "usage": 131072
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "value",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_combat_charge"
  },
  {
    "args": [],
    "default_args": [],
    "name": "increment_cards_played_in_combat"
  },
  {
    "args": [],
    "default_args": [],
    "name": "increment_non_kink_cards_played_in_combat"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "charge_id",
        "type": 0,
        "usage": 131072
      }
    ],
    "default_args": [],
    "name": "get_combat_charge"
  }
]
```

**Signals:**

```text
round_changed
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 8

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "cost": 1.0,
        "description_key": "reduce_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": -7.0
          },
          {
            "slot": "secondary",
            "stat_name": "PITY",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 1
          }
        ],
        "id": "deep_breath",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-57941-4078609272",
        "upgrade_count": 1,
        "upgrade_descriptions": [
          {
            "key": "upgrade_hope_description",
            "upgrade_id": "hope"
          }
        ],
        "upgrades": [
          {
            "upgrade_id": "hope",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "deep_breath"
    }
  ],
  "card_image": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "Deep Breath"
    }
  ],
  "card_uid": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "1791739655-57941-4078609272"
    }
  ],
  "character_border": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": -7.0
        },
        {
          "duration": 0,
          "stat_name": "PITY",
          "targets": [
            "player"
          ],
          "value": 1
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@1002",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371102363839851> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1002/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 8

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "available_in_floors": [],
        "cost": 2.0,
        "description_key": "deal_arousal_and_chance_status",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 12.0
          },
          {
            "chance": 0.45,
            "luck_proc": true,
            "placeholder_id": 2.0,
            "slot": "chance",
            "stat_name": "HORNY",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 2.0
          }
        ],
        "id": "daring_display",
        "name": "Daring Display",
        "rarity": "common",
        "repeat": 1,
        "source_deck": "moira",
        "tags": [
          "arousal",
          "horny",
          "soak"
        ],
        "type": "luck",
        "uid": "1791739655-57941-4273409655",
        "upgrade_count": 1,
        "upgrade_descriptions": [
          {
            "key": "upgrade_echo_description",
            "upgrade_id": "echo"
          }
        ],
        "upgrades": [
          {
            "upgrade_id": "echo",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "daring_display"
    }
  ],
  "card_image": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "Daring Display"
    }
  ],
  "card_uid": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "1791739655-57941-4273409655"
    }
  ],
  "character_border": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 2
    }
  ],
  "created_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 12.0
        },
        {
          "duration": 0,
          "stat_name": "HORNY",
          "targets": [
            "enemy"
          ],
          "value": 2.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@1031",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371097582333532> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        "arousal",
        "horny",
        "soak"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1031/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 8

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "available_in_floors": [],
        "cost": 1.0,
        "description_key": "deal_willpower_and_reduce_enemy_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "WILLPOWER",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": -6.0
          },
          {
            "placeholder_id": 2.0,
            "slot": "secondary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": -2.0
          }
        ],
        "id": "mock",
        "name": "Mock",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "willpower"
        ],
        "type": "general",
        "uid": "1791739655-57941-165729235",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "mock"
    }
  ],
  "card_image": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "Mock"
    }
  ],
  "card_uid": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "1791739655-57941-165729235"
    }
  ],
  "character_border": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "duration": 0,
          "stat_name": "WILLPOWER",
          "targets": [
            "enemy"
          ],
          "value": -6.0
        },
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": -2.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@1063",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371092901490350> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        "willpower"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1063/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 8

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "available_in_floors": [],
        "cost": 1.0,
        "description_key": "chance_deal_arousal_or_deal_arousal",
        "effects": [
          {
            "chance": 0.4,
            "luck_proc": true,
            "on_luck_fail": {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 4
            },
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 9.0
          }
        ],
        "id": "feeler",
        "name": "Feeler",
        "rarity": "common",
        "sex_type": "versatile",
        "source_deck": "moira",
        "tags": [
          "arousal",
          "luck"
        ],
        "type": "general",
        "uid": "1791739655-57941-1954779341",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "feeler"
    }
  ],
  "card_image": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "Feeler"
    }
  ],
  "card_uid": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "1791739655-57941-1954779341"
    }
  ],
  "character_border": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 9.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@1098",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371088002542674> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "versatile"
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        "arousal",
        "luck"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@1098/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 22, 23, 24, 25

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "available_in_floors": [],
        "cost": 1.0,
        "description_key": "chance_deal_arousal_or_deal_arousal",
        "effects": [
          {
            "chance": 0.4,
            "luck_proc": true,
            "on_luck_fail": {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 4
            },
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 9.0
          }
        ],
        "id": "feeler",
        "is_pinned": false,
        "name": "Feeler",
        "rarity": "common",
        "sex_type": "versatile",
        "source_deck": "moira",
        "tags": [
          "arousal",
          "luck"
        ],
        "type": "general",
        "uid": "1791739655-57941-1954779341",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "feeler"
    }
  ],
  "card_image": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "Feeler"
    }
  ],
  "card_uid": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "1791739655-57941-1954779341"
    }
  ],
  "character_border": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 9.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@11564",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223367797470389467> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "versatile"
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        "arousal",
        "luck"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11564/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 22, 23, 24, 25

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "cost": 1.0,
        "description_key": "reduce_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": -5.0
          }
        ],
        "id": "sitting_pretty",
        "is_pinned": false,
        "rarity": "common",
        "sex_type": "versatile",
        "sex_type_change": 1.0,
        "source_deck": "moira",
        "tags": [
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-57941-2477156348",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "sitting_pretty"
    }
  ],
  "card_image": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "Sitting Pretty"
    }
  ],
  "card_uid": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "1791739655-57941-2477156348"
    }
  ],
  "character_border": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": -5.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@11593",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223367791413814889> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "versatile"
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11593/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 22, 23, 24, 25

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "cost": 1.0,
        "description_key": "deal_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 5
          }
        ],
        "id": "lick",
        "name": "Lick",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal"
        ],
        "type": "general",
        "uid": "1791739655-57941-2508166965",
        "upgrade_count": 1,
        "upgrades": [
          {
            "upgrade_id": "limp",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "lick"
    }
  ],
  "card_image": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "Lick"
    }
  ],
  "card_uid": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "1791739655-57941-2508166965"
    }
  ],
  "character_border": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 5
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@11625",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223367784434493035> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        "arousal"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11625/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 22, 23, 24, 25

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 1.0,
        "description_key": "draw_cards",
        "effects": [
          {
            "action_id": "DRAW_CARDS",
            "placeholder_id": 1.0,
            "slot": "primary",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 3.0
          }
        ],
        "id": "read_the_room",
        "name": "Read the Room",
        "rarity": "uncommon",
        "reward_type": "card",
        "source_deck": "moira",
        "tags": [
          "draw_cards"
        ],
        "type": "general",
        "uid": "1791739655-319594-537699929",
        "upgrade_count": 1,
        "upgrades": [
          {
            "upgrade_id": "dud",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "read_the_room"
    }
  ],
  "card_image": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "Read the Room"
    }
  ],
  "card_uid": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "1791739655-319594-537699929"
    }
  ],
  "character_border": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        {
          "duration": 0,
          "stat_name": "",
          "targets": [
            "player"
          ],
          "value": 3.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@11660",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223367776683418882> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": [
        "draw_cards"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 22,
      "timestamp": "2026-10-11T14:34:56",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@11660/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 28, 29

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 1.0,
        "description_key": "self_arousal_and_arousal_all_enemies",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 3.0
          },
          {
            "placeholder_id": 2.0,
            "slot": "secondary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "all_enemies"
              ],
              "size": 1
            },
            "value": 11.0
          }
        ],
        "id": "desperation",
        "isImplemented": "true",
        "is_pinned": false,
        "name": "Desperation",
        "rarity": "uncommon",
        "reward_type": "card",
        "sex_type": "anal",
        "sex_type_enum": 2,
        "source_deck": "moira",
        "tags": [
          "arousal",
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-179203-1032050411",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "desperation"
    }
  ],
  "card_image": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "Desperation"
    }
  ],
  "card_uid": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "1791739655-179203-1032050411"
    }
  ],
  "character_border": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": 3.0
        },
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "all_enemies"
          ],
          "value": 11.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@18715",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223365471728821631> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "anal"
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        "arousal",
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18715/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 28, 29

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "available_in_floors": [],
        "cost": 1.0,
        "description_key": "deal_willpower_and_reduce_enemy_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "WILLPOWER",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": -6.0
          },
          {
            "placeholder_id": 2.0,
            "slot": "secondary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": -2.0
          }
        ],
        "id": "mock",
        "name": "Mock",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "willpower"
        ],
        "type": "general",
        "uid": "1791739655-57941-165729235",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "mock"
    }
  ],
  "card_image": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "Mock"
    }
  ],
  "card_uid": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "1791739655-57941-165729235"
    }
  ],
  "character_border": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        {
          "duration": 0,
          "stat_name": "WILLPOWER",
          "targets": [
            "enemy"
          ],
          "value": -6.0
        },
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": -2.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@18782",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223365471544275864> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": [
        "willpower"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 28,
      "timestamp": "2026-10-11T14:38:49",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@18782/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 9, 10, 11, 12, 13

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "cost": 1.0,
        "description_key": "reduce_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": -5
          }
        ],
        "id": "deep_breath",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-57941-487113934",
        "upgrade_count": 1,
        "upgrades": [
          {
            "upgrade_id": "damp",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "deep_breath"
    }
  ],
  "card_image": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "Deep Breath"
    }
  ],
  "card_uid": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "1791739655-57941-487113934"
    }
  ],
  "character_border": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": -5
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@2498",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370616512441041> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": [
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2498/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 9, 10, 11, 12, 13

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "cost": 1.0,
        "description_key": "reduce_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": -5.0
          }
        ],
        "id": "sitting_pretty",
        "is_pinned": false,
        "rarity": "common",
        "sex_type": "versatile",
        "sex_type_change": 1.0,
        "source_deck": "moira",
        "tags": [
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-57941-2477156348",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "sitting_pretty"
    }
  ],
  "card_image": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "Sitting Pretty"
    }
  ],
  "card_uid": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "1791739655-57941-2477156348"
    }
  ],
  "character_border": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": -5.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@2559",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370616344669781> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": "versatile"
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": [
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 9,
      "timestamp": "2026-10-11T14:29:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@2559/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 17

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 1.0,
        "description_key": "self_arousal_and_arousal_all_enemies",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 3.0
          },
          {
            "placeholder_id": 2.0,
            "slot": "secondary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "all_enemies"
              ],
              "size": 1
            },
            "value": 11.0
          }
        ],
        "id": "desperation",
        "isImplemented": "true",
        "name": "Desperation",
        "rarity": "uncommon",
        "reward_type": "card",
        "sex_type": "anal",
        "sex_type_enum": 2,
        "source_deck": "moira",
        "tags": [
          "arousal",
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-179203-1032050411",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "desperation"
    }
  ],
  "card_image": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "Desperation"
    }
  ],
  "card_uid": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "1791739655-179203-1032050411"
    }
  ],
  "character_border": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": 3.0
        },
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "all_enemies"
          ],
          "value": 11.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370166480398730> (bound to CardDisplay)"
      }
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@3628",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370182368422466> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "anal"
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        "arousal",
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3628/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 17

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "cost": 1.0,
        "description_key": "deal_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 7.0
          }
        ],
        "id": "lick",
        "name": "Lick",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal"
        ],
        "type": "general",
        "uid": "1791739655-57941-3941135162",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "lick"
    }
  ],
  "card_image": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "Lick"
    }
  ],
  "card_uid": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "1791739655-57941-3941135162"
    }
  ],
  "character_border": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 7.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<SceneTreeTimer#-9223370166413289666>"
      }
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@3657",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370177503030161> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        "arousal"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3657/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 17

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "cost": 1.0,
        "description_key": "reduce_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": -7.0
          },
          {
            "slot": "secondary",
            "stat_name": "PITY",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 1
          }
        ],
        "id": "deep_breath",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-57941-4078609272",
        "upgrade_count": 1,
        "upgrade_descriptions": [
          {
            "key": "upgrade_hope_description",
            "upgrade_id": "hope"
          }
        ],
        "upgrades": [
          {
            "upgrade_id": "hope",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "deep_breath"
    }
  ],
  "card_image": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "Deep Breath"
    }
  ],
  "card_uid": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "1791739655-57941-4078609272"
    }
  ],
  "character_border": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": -7.0
        },
        {
          "duration": 0,
          "stat_name": "PITY",
          "targets": [
            "player"
          ],
          "value": 1
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@3695",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370173124176789> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3695/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 17

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "cost": 1.0,
        "description_key": "reduce_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": -5
          }
        ],
        "id": "deep_breath",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-57941-487113934",
        "upgrade_count": 1,
        "upgrades": [
          {
            "upgrade_id": "damp",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "deep_breath"
    }
  ],
  "card_image": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "Deep Breath"
    }
  ],
  "card_uid": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "1791739655-57941-487113934"
    }
  ],
  "character_border": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": -5
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@3730",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": true
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370168426557782> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@3730/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 18, 19

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "cost": 1.0,
        "description_key": "deal_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 7.0
          }
        ],
        "id": "lick",
        "name": "Lick",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal"
        ],
        "type": "general",
        "uid": "1791739655-57941-3941135162",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "lick"
    }
  ],
  "card_image": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "Lick"
    }
  ],
  "card_uid": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "1791739655-57941-3941135162"
    }
  ],
  "character_border": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 7.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@5159",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223369678515071525> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": [
        "arousal"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/@Control@5159/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 8, 17, 18, 19

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "cost": 1.0,
        "description_key": "reduce_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": -5.0
          }
        ],
        "id": "sitting_pretty",
        "rarity": "common",
        "sex_type": "versatile",
        "sex_type_change": 1.0,
        "source_deck": "moira",
        "tags": [
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-57941-2477156348",
        "upgrade_count": 1,
        "upgrades": []
      }
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "available_in_floors": [],
        "cost": 1.0,
        "description_key": "chance_deal_arousal_or_deal_arousal",
        "effects": [
          {
            "chance": 0.4,
            "luck_proc": true,
            "on_luck_fail": {
              "_kind": "Dictionary",
              "keys_sample": [
                "stat_name",
                "value",
                "targets",
                "placeholder_id"
              ],
              "size": 4
            },
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 9.0
          }
        ],
        "id": "feeler",
        "name": "Feeler",
        "rarity": "common",
        "sex_type": "versatile",
        "source_deck": "moira",
        "tags": [
          "arousal",
          "luck"
        ],
        "type": "general",
        "uid": "1791739655-57941-1954779341",
        "upgrade_count": 1,
        "upgrades": []
      }
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "cost": 1.0,
        "description_key": "deal_arousal",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 5
          }
        ],
        "id": "lick",
        "name": "Lick",
        "rarity": "common",
        "source_deck": "moira",
        "tags": [
          "arousal"
        ],
        "type": "general",
        "uid": "1791739655-57941-2508166965",
        "upgrade_count": 1,
        "upgrades": [
          {
            "upgrade_id": "limp",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "sitting_pretty"
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "feeler"
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "lick"
    }
  ],
  "card_image": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "Sitting Pretty"
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "Feeler"
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "Lick"
    }
  ],
  "card_uid": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "1791739655-57941-2477156348"
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": "1791739655-57941-1954779341"
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": "1791739655-57941-2508166965"
    }
  ],
  "character_border": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "hand"
    }
  ],
  "description_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": -5.0
        }
      ]
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 9.0
        }
      ]
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 5
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370169198308028> (bound to CardDisplay)"
      }
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Card",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": true
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223371108202311206> (bound to CardDisplay)"
      }
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370186327845246> (bound to CardDisplay)"
      }
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223369678682843595> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": "versatile"
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": [
        "arousal_reduction"
      ]
    },
    {
      "snapshot": 17,
      "timestamp": "2026-10-11T14:30:38",
      "value": [
        "arousal",
        "luck"
      ]
    },
    {
      "snapshot": 18,
      "timestamp": "2026-10-11T14:32:03",
      "value": [
        "arousal"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 8,
      "timestamp": "2026-10-11T14:28:32",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/HandMargin/HandControl/Card/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 23

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 2.0,
        "description_key": "scale_reduce_arousal_on_pity",
        "effects": [
          {
            "placeholder_id": 1.0,
            "scales_on": "player_pity_stacks",
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": -4.0
          }
        ],
        "id": "ease_off",
        "name": "Ease Off",
        "rarity": "uncommon",
        "reward_type": "card",
        "source_deck": "moira",
        "tags": [
          "pity",
          "arousal_reduction"
        ],
        "type": "luck",
        "uid": "1791739655-498327-1753309129",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "ease_off"
    }
  ],
  "card_image": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "Ease Off"
    }
  ],
  "card_uid": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "1791739655-498327-1753309129"
    }
  ],
  "character_border": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": 2
    }
  ],
  "created_icon": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": -4.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@11791",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": [
        "pity",
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11791/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 23

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 1.0,
        "description_key": "deal_arousal_and_draw_card",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 8.0
          },
          {
            "action_id": "DRAW_CARDS",
            "placeholder_id": 2.0,
            "slot": "primary",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 1.0
          }
        ],
        "id": "perky_pull",
        "name": "Perky Pull",
        "rarity": "uncommon",
        "reward_type": "card",
        "source_deck": "moira",
        "tags": [
          "draw_cards",
          "arousal"
        ],
        "type": "trick",
        "uid": "1791739655-498327-3730739093",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "perky_pull"
    }
  ],
  "card_image": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "Perky Pull"
    }
  ],
  "card_uid": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "1791739655-498327-3730739093"
    }
  ],
  "character_border": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 8.0
        },
        {
          "duration": 0,
          "stat_name": "",
          "targets": [
            "player"
          ],
          "value": 1.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@11805",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": [
        "draw_cards",
        "arousal"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 23,
      "timestamp": "2026-10-11T14:35:01",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@11805/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 29

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 1.0,
        "description_key": "thrill_seeker_description",
        "effects": [
          {
            "can_stack": true,
            "ignores_modifiers": true,
            "placeholder_id": 2.0,
            "slot": "triggered",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "triggered_by": "luck_proc",
            "value": 1.0
          }
        ],
        "id": "thrill_seeker",
        "passive_kink_effect": {
          "action": "modify_luck_chance_passive",
          "chance": 0.12,
          "placeholder_id": 1.0
        },
        "rarity": "rare",
        "reward_type": "card",
        "source_deck": "moira",
        "tags": [
          "pity",
          "arousal"
        ],
        "type": "kink",
        "uid": "1791739655-729900-1587266921",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "thrill_seeker"
    }
  ],
  "card_image": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "Thrill Seeker"
    }
  ],
  "card_uid": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "1791739655-729900-1587266921"
    }
  ],
  "character_border": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": 1.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@19029",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": [
        "pity",
        "arousal"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19029/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 29

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 1.0,
        "description_key": "deal_arousal_and_gain_stack",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "enemy"
              ],
              "size": 1
            },
            "value": 9.0
          },
          {
            "placeholder_id": 2.0,
            "slot": "secondary",
            "stat_name": "LUCKY",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 1.0
          }
        ],
        "id": "tease",
        "name": "Tease",
        "rarity": "rare",
        "reward_type": "card",
        "source_deck": "moira",
        "tags": [
          "arousal",
          "lucky"
        ],
        "type": "general",
        "uid": "1791739655-729901-1687377142",
        "upgrade_count": 2,
        "upgrades": [
          {
            "upgrade_id": "dud",
            "upgrade_index": 0
          }
        ]
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "tease"
    }
  ],
  "card_image": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "Tease"
    }
  ],
  "card_uid": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "1791739655-729901-1687377142"
    }
  ],
  "character_border": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "enemy"
          ],
          "value": 9.0
        },
        {
          "duration": 0,
          "stat_name": "LUCKY",
          "targets": [
            "player"
          ],
          "value": 1.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "energy_label": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@19043",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": false
    }
  ],
  "name_label": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": ""
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": [
        "arousal",
        "lucky"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 29,
      "timestamp": "2026-10-11T14:38:54",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@19043/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```


### CardDisplay — `/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay`

- **Class:** `Control`
- **Script:** `res://Cards/CardDisplay.gd`
- **Roles:** scene_node
- **Seen in snapshots:** 11, 12

**Script property values (only changes are listed):**

```json
{
  "_face_populated": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": true
    }
  ],
  "_fallback_card_id": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "bluff"
    }
  ],
  "_is_showing_upgrade_preview": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": false
    }
  ],
  "_on_mouse_entered_callback": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_on_mouse_exited_callback": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Callable",
        "value": "null::null"
      }
    }
  ],
  "_original_card_data_before_preview": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {}
    }
  ],
  "_tap_origin": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "(0.0, 0.0)"
    }
  ],
  "_tap_started": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": false
    }
  ],
  "card_data": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "available_in_floors": [
          1.0,
          2.0,
          3.0
        ],
        "cost": 1.0,
        "description_key": "self_arousal_and_arousal_all_enemies",
        "effects": [
          {
            "placeholder_id": 1.0,
            "slot": "primary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "player"
              ],
              "size": 1
            },
            "value": 3.0
          },
          {
            "placeholder_id": 2.0,
            "slot": "secondary",
            "stat_name": "AROUSAL",
            "targets": {
              "_kind": "Array",
              "sample": [
                "all_enemies"
              ],
              "size": 1
            },
            "value": 11.0
          }
        ],
        "id": "desperation",
        "isImplemented": "true",
        "name": "Desperation",
        "rarity": "uncommon",
        "reward_type": "card",
        "sex_type": "anal",
        "sex_type_enum": 2,
        "source_deck": "moira",
        "tags": [
          "arousal",
          "arousal_reduction"
        ],
        "type": "general",
        "uid": "1791739655-179203-1032050411",
        "upgrade_count": 1,
        "upgrades": []
      }
    }
  ],
  "card_id": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "desperation"
    }
  ],
  "card_image": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CardImage",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CardArt/CardImage"
      }
    }
  ],
  "card_name_text": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "Desperation"
    }
  ],
  "card_uid": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "1791739655-179203-1032050411"
    }
  ],
  "character_border": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CharacterFrame",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/CardMargin/CharacterFrame"
      }
    }
  ],
  "class_energy_material": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Resource",
        "class": "ShaderMaterial",
        "path": ""
      }
    }
  ],
  "class_energy_rect": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "ClassEnergy",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy"
      }
    }
  ],
  "cost": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": 1
    }
  ],
  "created_icon": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "CreatedIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/CreatedIcon"
      }
    }
  ],
  "current_interaction_mode": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "selection_choice"
    }
  ],
  "description_label": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "DescriptionLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer/DescriptionLabel"
      }
    }
  ],
  "description_margin_container": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "MarginContainer",
        "name": "DescriptionMarginContainer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/DescriptionMarginContainer"
      }
    }
  ],
  "description_text": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "No description available."
    }
  ],
  "effects": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": [
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "player"
          ],
          "value": 3.0
        },
        {
          "duration": 0,
          "stat_name": "AROUSAL",
          "targets": [
            "all_enemies"
          ],
          "value": 11.0
        }
      ]
    }
  ],
  "effects_list_canvas_layer_ref": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "EffectsListCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/EffectsListCanvasLayer"
      }
    }
  ],
  "effects_list_delay_timer": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": null
    }
  ],
  "effects_list_fade_tween": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": null
    },
    {
      "snapshot": 12,
      "timestamp": "2026-10-11T14:30:01",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370492411375000> (bound to CardDisplay)"
      }
    }
  ],
  "effects_list_node": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": null
    },
    {
      "snapshot": 12,
      "timestamp": "2026-10-11T14:30:01",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "CardEffect",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/EffectsListCanvasLayer/CardEffect"
      }
    }
  ],
  "energy_label": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "EnergyLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/ClassEnergy/EnergyLabel"
      }
    }
  ],
  "host_node": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "@Control@2828",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828"
      }
    }
  ],
  "hover_scale_tween": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": null
    }
  ],
  "initial_card_id": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": ""
    }
  ],
  "initial_scale": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "(1.0, 1.0)"
    }
  ],
  "is_mouse_inside": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": false
    },
    {
      "snapshot": 12,
      "timestamp": "2026-10-11T14:30:01",
      "value": true
    }
  ],
  "is_playable_in_hand": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": false
    }
  ],
  "is_selected_for_choice": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": false
    },
    {
      "snapshot": 12,
      "timestamp": "2026-10-11T14:30:01",
      "value": true
    }
  ],
  "name_label": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "NameLabel",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner/NameLabel"
      }
    }
  ],
  "playable_glow": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "NinePatchRect",
        "name": "PlayableGlow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/PlayableGlow"
      }
    }
  ],
  "playable_glow_intensity_tween": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": null
    },
    {
      "snapshot": 12,
      "timestamp": "2026-10-11T14:30:01",
      "value": {
        "_kind": "Object",
        "value": "<Tween#-9223370492377819521> (bound to CardDisplay)"
      }
    }
  ],
  "preview_canvas_layer": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "CanvasLayer",
        "name": "PreviewCanvasLayer",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/PreviewCanvasLayer"
      }
    }
  ],
  "preview_card_node": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": null
    }
  ],
  "preview_cycle_tween": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": null
    }
  ],
  "preview_pool": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": []
    }
  ],
  "preview_pool_index": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": 0
    }
  ],
  "rarity_banner": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "RarityBanner",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/RarityBanner"
      }
    }
  ],
  "resting_scale": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "(1.0, 1.0)"
    }
  ],
  "resting_z_index": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": 0
    }
  ],
  "scaler": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "Control",
        "name": "Scaler",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler"
      }
    }
  ],
  "sex_type": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": "anal"
    }
  ],
  "sex_type2_shadow": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2/SexType2Shadow"
      }
    }
  ],
  "sex_type3_shadow": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3Shadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3/SexType3Shadow"
      }
    }
  ],
  "sex_type_icon": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType"
      }
    }
  ],
  "sex_type_icon2": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType2"
      }
    }
  ],
  "sex_type_icon3": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexType3",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType3"
      }
    }
  ],
  "sex_type_shadow": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SexTypeShadow",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/SexType/SexTypeShadow"
      }
    }
  ],
  "soak_icon": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "TextureRect",
        "name": "SoakIcon",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/DescriptionBackground/SoakIcon"
      }
    }
  ],
  "tags": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": [
        "arousal",
        "arousal_reduction"
      ]
    }
  ],
  "targets_arr": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": []
    }
  ],
  "upgrade_label_1": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel1",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel1"
      }
    }
  ],
  "upgrade_label_2": [
    {
      "snapshot": 11,
      "timestamp": "2026-10-11T14:29:51",
      "value": {
        "_kind": "Node",
        "class": "RichTextLabel",
        "name": "UpgradeLabel2",
        "path": "/root/GameRoot/SceneLoader/Combat/CanvasLayer/UI_Container/Rewards/RewardSelect/OptionsHBoxContainer/@Control@2828/Scaler/CardSurface/SubViewport/CardDisplay/Scaler/Overlay/HBoxContainer/UpgradeLabel2"
      }
    }
  ]
}
```

**Method names (keyword-filtered scene methods):**

```text
@initial_card_id_setter, _advance_preview_pool, _apply_upgrade_glow, _clear_upgrade_glow, _fit_upgrade_chip, _on_effects_list_delay_finished, _set_empty_upgrade_label, _set_upgrade_label, _setup_rendering_properties, _start_preview_cycle, display_card, display_upgrades, get_card_from_run_deck_by_uid, hide_upgrade_preview, load_and_display_card_data, notify_hover_ended, notify_hover_started, parse_card_description, reinitialize_card, set_fallback_card_id, set_selectable_state, set_selection_highlight, setup_as_choice_option, show_upgrade_preview
```

**Relevant method signatures:**

```json
[
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "@initial_card_id_setter"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "raw_text",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "parse_card_description"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "p_card_uid_or_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "load_and_display_card_data"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "display_upgrades"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrades",
        "type": 28,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "idx",
        "type": 2,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      },
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "colour_hex",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_apply_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_fit_upgrade_chip"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_clear_upgrade_glow"
  },
  {
    "args": [
      {
        "class_name": "RichTextLabel",
        "hint": 0,
        "hint_string": "",
        "name": "label",
        "type": 24,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "_set_empty_upgrade_label"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "uid",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "get_card_from_run_deck_by_uid"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "fallback_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_fallback_card_id"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "new_card_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "reinitialize_card"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "data",
        "type": 27,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "setup_as_choice_option"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "is_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selection_highlight"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "can_be_selected",
        "type": 1,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "set_selectable_state"
  },
  {
    "args": [
      {
        "class_name": "",
        "hint": 0,
        "hint_string": "",
        "name": "upgrade_id",
        "type": 4,
        "usage": 0
      }
    ],
    "default_args": [],
    "name": "show_upgrade_preview"
  },
  {
    "args": [],
    "default_args": [],
    "name": "hide_upgrade_preview"
  }
]
```

**Signals:**

```text
selection_clicked
```

