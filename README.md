**Java backend developer in Piauí, Brazil.** I learned Java on Minecraft servers, where many players change shared state at the same time and every tick has to finish in 50 ms. Now I build Spring Boot REST APIs, per-server caches invalidated through Redis, and plugins that keep I/O off the main thread. I also make websites and apps for small businesses.

**Currently** building *Convergência*, an MMORPG-style Minecraft server with a single-currency economy, a player market, pets and mounts. It lives in a private repo, like most of my day-to-day work.

### Selected work

**Player stats platform** · [stats-paper-plugin](https://github.com/kassiin/stats-paper-plugin) → [stats-api-rest](https://github.com/kassiin/stats-api-rest) → [stats-dashboard](https://github.com/kassiin/stats-dashboard)\
The game server caches stats in Caffeine and calls a Spring Boot 3 API from a worker pool. The API stores them with JPA and publishes cache invalidations over Redis Pub/Sub, so other servers evict their stale copies. A React dashboard reads the same API.

**RPG server core** · [dungeons-core-plugin](https://github.com/kassiin/dungeons-core-plugin)\
12 Gradle modules (classes, attributes, weapons, crates, dungeons, events, i18n) that build on shared API and commons modules. A core module bundles them into one shaded JAR for Paper 1.21 on Java 21.

**Schematic construction engine** · [flare-constructor](https://github.com/kassiin/flare-constructor)\
NPC builders rebuild schematics through a step pipeline (intro, preparation, build, patrol), sending block updates as async packets inside protected worksites.

### Stack

**Backend:** Java 21, Spring Boot 3, JPA, Redis, MySQL, MongoDB, Docker, Gradle\
**Minecraft:** Paper, NeoForge, Fabric\
**Also:** TypeScript, React, Astro, Node, Python, Blockbench (3D models and animation)

Open to Java backend roles · [Discord](https://discord.com/users/531456654462681088)
