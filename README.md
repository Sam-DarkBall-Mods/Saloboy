# Saloboy

[![CI](https://github.com/Sam-DarkBall-Mods/Saloboy/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Saloboy/actions/workflows/ci.yml)

Saloboy adds the T50 pistol, its single round magazine, ammunition, model and
sounds. The mod does not add vehicles or scripted systems.

## Requirements

- Arma 3 2.22 or newer

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The weapon classes and the `saloboy` PBO prefix stay unchanged so saved
loadouts continue to resolve them.

## License

Code and configs use GPL-2.0-or-later. The weapon model, textures, materials and
audio use APL-SA. See [LICENSES.md](LICENSES.md).
