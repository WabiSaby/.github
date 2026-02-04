# Wabi Saby

**Music streaming platform that aggregates content from multiple sources through plugins.** Stream from Spotify, YouTube, and more in one unified experience—like Stremio for music.

Multi-tenant SaaS with an extensible plugin ecosystem, built with Go.

## Repositories

| Repository | Description |
|------------|-------------|
| [wabisaby-devkit](https://github.com/wabisaby/wabisaby-devkit) | Meta-repo and desktop app for platform development. Manage projects, run services, and work with the local stack (Wails + Go + React). |
| [wabisaby-core](https://github.com/wabisaby/wabisaby-core) | Main backend: API, WebSocket, plugin workers, and core services. Clean Architecture, Go. |
| [wabisaby-plugin-sdk-go](https://github.com/wabisaby/wabisaby-plugin-sdk-go) | Go SDK for building Wabi Saby source plugins. |
| [wabisaby-protos](https://github.com/wabisaby/wabisaby-protos) | Protocol buffer definitions for Wabi Saby services and plugins. |
| [wabisaby-plugins](https://github.com/wabisaby/wabisaby-plugins) | Official and community plugins (e.g. network storage). |

## Getting started

- **Developing the platform** — Clone [wabisaby-devkit](https://github.com/wabisaby/wabisaby-devkit), run `git submodule update --init --recursive`, then `make start` to run the DevKit desktop app and work with all projects in one tree.
- **Building a plugin** — Use [wabisaby-plugin-sdk-go](https://github.com/wabisaby/wabisaby-plugin-sdk-go) and see [wabisaby-plugins](https://github.com/wabisaby/wabisaby-plugins) for examples.

## Project structure

- **wabisaby-core** — API, WebSocket, gRPC capabilities server, and stateful/stateless plugin workers.
- **wabisaby-protos** — Shared Protocol Buffers; consumed by core and plugins.
- **wabisaby-plugin-sdk-go** — SDK for implementing source plugins in Go.
- **wabisaby-devkit** — Meta-repo (submodules) + desktop app for managing projects and local infrastructure (Docker, services, logs).

## Contact

For questions or collaboration, open an issue or discussion in the relevant repository.
