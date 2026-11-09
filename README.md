# Hi, I’m Johan Näslund

I’m a software engineer and systems architect. I’ve built products and systems from scratch for businesses large and small, working across a range of languages and frameworks. These days, I’m building a multiplayer game and sharing the tools I build here on GitHub. You can learn more about me and read my writing at [humacss.dev](https://humacss.dev/).

## Open Source

I’ve built a few tools that I share as open source. Here’s what each one does.

- [ConTime](https://github.com/humacss/contime) helps systems process events over time, including when they arrive late or out of order.
- [Minbin](https://github.com/humacss/minbin) is a minimal binary serialization library for exchanging data across platforms.
- [TraitStub](https://github.com/humacss/traitstub) generates lightweight Rust trait stubs so you can test real code with controlled dependencies.
- [ContentID](https://github.com/humacss/contentid) lets independent programs generate the same ID from the same content without a central service.

You can see ConTime and Minbin in action in the shared asteroid game on [my website](https://humacss.dev/).

## What I’m Building

I’m building [Arcanex](https://arcanex.online/investors/), a Rust multiplayer game engine that handles reconciliation so game developers don’t have to. Its state management is built on [ConTime](https://github.com/humacss/contime), an open-source Rust library I created to reconstruct deterministic state from event history, even when events arrive late or out of order.

On top of ConTime, I built a modular server runtime combining reactive processing with event streaming between server processes and clients. When earlier state changes, the runtime removes outdated results and updates the systems that used them. Each process automatically subscribes to the history it needs through channel-based permissions and maintains its own in-memory view.

I’m using this engine to build [Arcanex Online](https://arcanex.online/), a persistent world where players can build towns, form communities, and leave a lasting mark. The broader goal is to make worlds like this practical for small teams to create and run. I’m currently bringing the engine and game together into a playable alpha.
