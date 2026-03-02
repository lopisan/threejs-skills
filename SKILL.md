---
name: threejs
description: Three.js 3D development - scene setup, geometry, materials, lighting, textures, animation, model loading, shaders, post-processing, and interaction. Use when creating 3D scenes, working with WebGL, building interactive 3D experiences, loading GLTF models, writing custom shaders, or any Three.js development.
---

# Three.js Skills

Complete Three.js reference (r160+) organized into topic-specific modules. **Read the relevant module(s) before writing Three.js code.**

## Reference Modules

Read the module matching your task using the Read tool. Multiple modules can be combined for complex tasks.

| Module | Path | Use when |
|--------|------|----------|
| **Fundamentals** | `skills/threejs-fundamentals/SKILL.md` | Scene setup, cameras, renderer, Object3D hierarchy, coordinate systems, transforms |
| **Geometry** | `skills/threejs-geometry/SKILL.md` | Built-in shapes, BufferGeometry, custom meshes, instanced rendering |
| **Materials** | `skills/threejs-materials/SKILL.md` | PBR materials, basic/phong/standard, shader materials, material properties |
| **Lighting** | `skills/threejs-lighting/SKILL.md` | Light types, shadows, environment lighting (IBL), light helpers |
| **Textures** | `skills/threejs-textures/SKILL.md` | Texture types, UV mapping, cubemaps, HDR environments, render targets |
| **Animation** | `skills/threejs-animation/SKILL.md` | Keyframe animation, skeletal animation, morph targets, animation mixing |
| **Loaders** | `skills/threejs-loaders/SKILL.md` | GLTF/GLB loading, texture loading, async patterns, progress tracking |
| **Shaders** | `skills/threejs-shaders/SKILL.md` | GLSL, ShaderMaterial, uniforms, custom vertex/fragment effects |
| **Post-processing** | `skills/threejs-postprocessing/SKILL.md` | EffectComposer, bloom, DOF, color grading, screen-space effects |
| **Interaction** | `skills/threejs-interaction/SKILL.md` | Raycasting, OrbitControls, mouse/touch input, object selection |

## Workflow

1. Identify which modules are relevant to the task
2. Read those modules with the Read tool (paths are relative to this skill's directory)
3. Follow the patterns and API signatures from the modules
4. Combine patterns from multiple modules as needed

## Common Task Routing

- **"Create a 3D scene"** → Read Fundamentals, then Lighting
- **"Load a GLTF model"** → Read Loaders, then Animation (if animated)
- **"Add visual effects"** → Read Post-processing, optionally Shaders
- **"Make it interactive"** → Read Interaction, then Fundamentals (for transforms)
- **"Custom shader effect"** → Read Shaders, then Materials
- **"Optimize performance"** → Read Geometry (instancing), Materials (merging), Lighting (baking)
