# Hi, I'm Johan Näslund

I'm a full-stack engineer and systems architect with 14+ years of experience building and operating software. My work spans enterprise APIs, data pipelines, AI agents, and Rust systems infrastructure. I've been a founding CTO, engineering manager, and lead engineer, and I stay hands-on with the code.

## What I'm building

I'm building [Arcanex](https://arcanex.online/investors/), a Rust multiplayer game engine that handles reconciliation so game developers don't have to. Its state management is built on [ConTime](https://github.com/humacss/contime), an open-source Rust library I created to reconstruct deterministic state from event history, even when events arrive late or out of order.

On top of ConTime, I built a modular server runtime combining reactive processing with event streaming between server processes and clients. When earlier state changes, the runtime removes outdated results and updates the systems that used them. Each process automatically subscribes to the history it needs through channel-based permissions and maintains its own in-memory view.

I'm using this engine to build Arcanex Online, a persistent world where players can build towns, form communities, and leave a lasting mark. The broader goal is to make worlds like this practical for small teams to create and run. I'm currently bringing the engine and game together into a playable alpha.

## Earlier work

At **Neuron X**, I launched Esper, a Shopify AI agent for natural-language data querying and ingestion. At **Zoomforth**, I built enterprise APIs and integrations, brought analytics ETL in-house to halve costs, and handled production incidents and recovery. Earlier, I built backend systems in Go and led work on accounting and CRM platforms.

I'm particularly interested in distributed systems, concurrency, performance, and how AI-assisted development changes the way we build reliable software.
