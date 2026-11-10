<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img src="./assets/banner-dark.svg" alt="CHIMERA banner" width="100%">
</picture>

<br>

<img src="https://img.shields.io/badge/WebAssembly-161B22?style=flat-square&labelColor=0D1117&logo=webassembly&logoColor=EF4444" alt="WebAssembly">
<img src="https://img.shields.io/badge/Three.js-161B22?style=flat-square&labelColor=0D1117&logo=threedotjs&logoColor=EF4444" alt="Three.js">
<img src="https://img.shields.io/badge/3D-161B22?style=flat-square&labelColor=0D1117&logo=blender&logoColor=EF4444" alt="3D">

<br><br>

<a href="#quick-start">Quick Start</a> · <a href="#features">Features</a>

</div>

## Overview

Anatomy is spatial, but most study material is flat. **CHIMERA** renders an interactive 3D anatomical model in the browser with pronunciation support, so structure and name are learned together instead of separately.

> **Scope note:** this repository contains the **compiled production build**, not the original source. It is kept as a live demonstration artifact and is not set up for modification.

## Features

| | |
|---|---|
| **3D anatomy viewer** | Rotatable model with labeled structures |
| **Pronunciation** | Dictionary-backed audio for anatomical terms |
| **WebAssembly core** | Heavy geometry work compiled to wasm for browser performance |
| **Zero build step** | Ships as static output — clone and serve |

## Stack

WebAssembly · Three.js · Vite build output · CMU pronouncing dictionary

## Quick Start

```bash
git clone https://github.com/tribetorkoz/chimera-anatomy.git
cd chimera-anatomy
npx serve .        # or open index.html via any static host
```


## License

MIT
