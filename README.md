# Introduction

Lyra is an **immutable, runtime-agnostic, edge, and in-memory full-text search engine** that works both on client and server.

Through implementing an optimized prefix tree and some clever tweaks, Lyra can perform searches through millions of entries in **microseconds**.

{% embed url="https://www.youtube.com/watch?v=42sMkbGLlh4" %}

## Requirements

A JavaScript runtime is the **only** requirement. Lyra has been designed to work on any runtime and has no dependencies.

## Installation

You can install Lyra using npm, yarn, pnpm:

```bash
npm install @lyrasearch/lyra
```

```bash
yarn add @lyrasearch/lyra
```

```bash
pnpm add @lyrasearch/lyra
```

Or import it directly in a browser module:

```html
<html>
  <body>
    <script type="module">
      import { create, search, insert } from "https://unpkg.com/@lyrasearch/lyra@latest/dist/esm/src/lyra.js";

      // ...
    </script>
  </body>
</html>
```
