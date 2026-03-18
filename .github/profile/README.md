# Bloom Engine

**Native games from TypeScript.**

Write TypeScript. Ship native games. No browser, no C++.
Bloom compiles your game to Metal, DirectX 12, Vulkan, and OpenGL — one codebase for every platform.

## What is Bloom?

Bloom is a native TypeScript game engine. You write your game in TypeScript and it compiles to true native binaries for macOS, Windows, Linux, iOS, and Android. No Electron, no WebView, no runtime overhead.

### Features

- **Simple API** — The entire API fits on a cheatsheet. Just functions, no magic.
- **True native** — Compiles to Metal, DirectX 12, Vulkan, and OpenGL via wgpu.
- **Unified 2D/3D** — Shapes, textures, text, models, and audio in one engine.
- **Ship everywhere** — macOS, Windows, Linux, iOS, Android from one codebase.
- **7 modular subsystems** — Core, Shapes, Textures, Text, Audio, Models, Math. Use only what you need.

### Quick start

```typescript
import { initWindow, windowShouldClose, beginDrawing,
         endDrawing, clearBackground, drawText, Colors } from "bloom";

initWindow(800, 450, "My Game");

while (!windowShouldClose()) {
  beginDrawing();
  clearBackground(Colors.RAYWHITE);
  drawText("Hello, Bloom!", 190, 200, 20, Colors.DARKGRAY);
  endDrawing();
}
```

## Repos

| Repo | Description |
|------|-------------|
| **[landing](https://github.com/Bloom-Engine/landing)** | Landing page — [bloomengine.dev](https://bloomengine.dev) |
| **[brand](https://github.com/Bloom-Engine/brand)** | Brand guidelines, colors, typography, and assets |

## Links

- [bloomengine.dev](https://bloomengine.dev)
- [Docs](https://bloomengine.dev/docs)
- [Showcase](https://bloomengine.dev/showcase)
