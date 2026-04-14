---
bundle:
  name: caveman
  version: 1.0.0
  description: "Ultra-terse LLM communication overlay. ~75% fewer output tokens."

includes:
  - bundle: git+https://github.com/microsoft/amplifier-foundation@main
  - bundle: caveman:behaviors/caveman
---
