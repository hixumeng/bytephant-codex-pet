# Bytephant

Bytephant is a cheerful animated elephant pet for Codex. It uses the Codex pet v2 format with nine standard animation states and sixteen clockwise look directions.

![Bytephant animation contact sheet](preview.png)

## Install

1. Download `pet.json` and `spritesheet.webp`.
2. Create `~/.codex/pets/bytephant/`.
3. Copy both files into that folder.
4. Restart Codex if Bytephant does not appear immediately.

Expected layout:

```text
~/.codex/pets/bytephant/
├── pet.json
└── spritesheet.webp
```

## Pet format

- Sprite format: WebP with transparency
- Atlas: 8 columns × 11 rows
- Cell size: 192 × 208 pixels
- Sprite version: 2
- Animations: idle, run right, run left, wave, jump, failed, waiting, working, review, and 16 look directions

## License

Bytephant's artwork and package files are released under the Creative Commons Attribution 4.0 International license. See [LICENSE](LICENSE).

## Credits

Created by Emon Xu with Codex.
