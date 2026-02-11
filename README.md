# snapmaker-skill

🖨️ Control and monitor Snapmaker 2.0 3D printers via their HTTP API.

An [OpenClaw](https://openclaw.ai) skill.

## Quick Start

```bash
# Discover Snapmaker printers on the network (no config needed)
python3 scripts/snapmaker.py discover

# Check printer status
python3 scripts/snapmaker.py status

# Watch print progress live
python3 scripts/snapmaker.py watch

# Send a file and start printing
python3 scripts/snapmaker.py send file.gcode --start --yes
```

See [SKILL.md](SKILL.md) for full documentation.

## Links

- **GitHub**: https://github.com/odrobnik/snapmaker-skill
- **ClawHub**: https://www.clawhub.com/skills/snapmaker-2
