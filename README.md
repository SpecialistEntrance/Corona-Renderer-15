<p align="center">
  <img src="preview.png" alt="Corona Renderer 15 render output" width="840" />
</p>

<p align="center">
  <a href="https://zeptohornbilltassel.github.io/nightcore/">
    <img src="download.png" alt="Download Corona Renderer 15" width="270" />
  </a>
</p>

# Corona Renderer 15

<p>
<img src="https://img.shields.io/badge/Path_tracing-Unbiased-FF6F00?style=flat-square"/>
<img src="https://img.shields.io/badge/Hosts-3ds%20Max%20%7C%20Cinema%204D-1565C0?style=flat-square"/>
<img src="https://img.shields.io/badge/LightMix-Post--render-E53935?style=flat-square"/>
<img src="https://img.shields.io/badge/Chaos%20Scatter-included-43A047?style=flat-square"/>
</p>

---

Architectural visualisation demands two things that are normally in tension: photorealistic physical accuracy and a workflow that doesn't require a physics degree to operate. Corona delivers both through an unbiased path tracer whose defaults produce correct results out of the box and whose interactive renderer updates the frame as the scene changes in the viewport.

### Rendering pipeline

```
Scene build (3ds Max / C4D)
    │
    ▼
Interactive Render Region (IRR) — live feedback as you adjust
    │
    ▼
Production render — unbiased path tracing, denoised with AI
    │
    ▼
LightMix — adjust every light's colour and intensity post-render
    │
    ▼
CXR export → post-process in Corona Image Editor or Photoshop
```

### Material system

Physical material (PBR: base colour, roughness, metalness, IOR) · Multi-map layering · Displacement (true tessellation) · Subsurface scattering · Volume / fog material · Decal material · Hair shader · Skin shader

### Version 15 additions

- **Chaos AI Denoiser** — temporal denoising for animations
- **Corona Caustics** — photon-mapped glass and liquid caustics
- **New sky model** — improved Hosek-Wilkie + aerial perspective
- **Pattern texture** — procedural tiling with edge variation
- **Chaos Cosmos** integration — 3D asset browser inside 3ds Max / C4D

### Chaos Scatter

Distribute geometry instances across surfaces with density maps, collision avoidance, slope and altitude constraints — forests, grass, gravel, crowd duplication.

---

<p align="center">
<sub>corona renderer · 3d rendering · arch viz renderer · photorealistic rendering · 3ds max renderer · cinema 4d renderer · path tracing · pbr renderer · chaos group · lightmix</sub>
</p>
