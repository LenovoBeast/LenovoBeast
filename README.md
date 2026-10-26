<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LenovoBeast/LenovoBeast/main/assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LenovoBeast/LenovoBeast/main/assets/banner-light.svg">
  <img src="https://raw.githubusercontent.com/LenovoBeast/LenovoBeast/main/assets/banner-dark.svg" width="100%" alt="Lenovo Beast — spatial interfaces, agent tooling, open source">
</picture>

<br>

I build the layer between a model and a finished thing: interfaces that hold up under motion,
tools that run on your own machine, and documentation that argues for itself instead of decorating.

**Four repositories on this account are mine. The rest are forks I read** — kept around to study how
other people solve the same problems, never presented as my work.

<p>
  <a href="https://lenovobeast.github.io/Lenovo-DevPort/"><img src="https://img.shields.io/badge/OPEN_THE_PORTAL-00d4ff?style=for-the-badge&labelColor=0b0d10" alt="Open the DevPort"></a>
  <a href="mailto:LenovoBeast.905@gmail.com"><img src="https://img.shields.io/badge/EMAIL-8b5cf6?style=for-the-badge&labelColor=0b0d10" alt="Email"></a>
</p>

---

## ◢ Flagship

### [Lenovo DevPort](https://lenovobeast.github.io/Lenovo-DevPort/) · [source](https://github.com/LenovoBeast/Lenovo-DevPort)

A developer portal rebuilt as a spatial interface. Live repository data drives the visuals, a 3D
centrepiece is lazy-loaded behind a static frame, and the design system is written down in
[`DESIGN_SYSTEM.md`](https://github.com/LenovoBeast/Lenovo-DevPort/blob/main/DESIGN_SYSTEM.md)
so the rules can be argued with.

The constraint that shaped it: **make the data the material**. Repository stats, languages and
activity feed the composition, and every section has to justify its space with something you can
read. Static export. No server, no database, no runtime dependencies.

`Next.js 14` · `TypeScript` · `Tailwind` · `Three.js / R3F` · `Framer Motion` · `GSAP`

---

## ◢ Also built

| Repository | What it is | Stack |
|---|---|---|
| [**Playground**](https://github.com/LenovoBeast/Playground) | An interactive Three.js dreamscape workspace with five playable mini-games. Preview is generated from the production site on every deploy. | JavaScript · Three.js · Actions |
| [**Jarvis**](https://github.com/LenovoBeast/Jarvis) | Everything needed to stand up a local, voice-enabled assistant: a setup guide, an interactive setup script, and the UI design for the assistant itself. | HTML · PowerShell |
| [**Beast-Invoice**](https://github.com/LenovoBeast/Beast-Invoice) | An invoice generator built for a garage counter, not an office. Every field is a dropdown, autocomplete or stepper — free text is the fallback. Under 60 seconds per invoice. | TypeScript · Zero build step |

---

## ◢ How I work

- **Motion explains state.** It never decorates empty space. If an animation isn't telling you
  something changed, it gets cut.
- **Glass is built, not blurred.** Layered gradients and inset highlights, so surfaces hold up on a
  low-contrast display instead of dissolving into it.
- **One accent family, used sparingly.** Blue → cyan → violet. The moment a fourth colour appears,
  nothing is emphasised anymore.
- **Live data needs an honest fallback.** Rate limits happen. The page shows real numbers, or it
  shows static ones — never a blank state.
- **Ship static by default.** If it can be a folder on a CDN, it should be.

---

## ◢ Stack

```
interface    TypeScript · React · Next.js · Tailwind · Three.js / R3F · GSAP
systems      Node.js · Python · Go · PostgreSQL · Redis · Docker
delivery     GitHub Actions · static export · edge CDN
environment  Arch Linux · zsh + starship · Neovim / VS Code
```

---

## ◢ Contact

**[LenovoBeast.905@gmail.com](mailto:LenovoBeast.905@gmail.com)** · [DevPort](https://lenovobeast.github.io/Lenovo-DevPort/) · [All repositories](https://github.com/LenovoBeast?tab=repositories)

<sub>Site source is MIT. If a number on this page disagrees with the repository, the repository wins.</sub>
