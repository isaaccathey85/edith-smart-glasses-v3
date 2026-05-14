# edith-smart-glasses-v3
edith-smart-glasses-v3/
├── README.md
├── CODEX_TASKS.md
├── requirements.txt
├── .env.example
├── config/
│   ├── settings.example.json
│   └── permissions.example.json
├── edith/
│   ├── main.py
│   ├── config.py
│   ├── wakeword.py
│   ├── speech_to_text.py
│   ├── ai_engine.py
│   ├── command_parser.py
│   ├── voice_output.py
│   ├── hud/
│   │   ├── oled_display.py
│   │   ├── hud_renderer.py
│   │   ├── visual_knowledge_engine.py
│   │   ├── diagram_renderer.py
│   │   └── graph_renderer.py
│   ├── vision/
│   │   ├── camera.py
│   │   ├── object_detection.py
│   │   └── scene_summary.py
│   ├── security/
│   │   ├── auth_manager.py
│   │   ├── voice_match.py
│   │   ├── face_profiles.py
│   │   └── permissions.py
│   ├── devices/
│   │   ├── bluetooth_manager.py
│   │   ├── device_control_hub.py
│   │   └── trusted_devices.py
│   ├── suit/
│   │   ├── suit_controller.py
│   │   └── serial_bridge.py
│   ├── memory/
│   │   ├── memory_store.py
│   │   └── semantic_memory.py
│   ├── modes/
│   │   ├── civilian_mode.py
│   │   ├── tactical_mode.py
│   │   ├── stealth_mode.py
│   │   ├── learning_mode.py
│   │   └── developer_mode.py
│   └── utils/
│       ├── logger.py
│       └── system_status.py
├── models/
│   └── vosk_model/
├── logs/
├── tests/
│   ├── test_command_parser.py
│   ├── test_permissions.py
│   └── test_visual_knowledge_engine.py
└── docs/
    ├── HARDWARE.md
    ├── COMMANDS.md
    ├── MODES.md
    ├── CODEX_PROMPTS.md
    └── ROADMAP.md
