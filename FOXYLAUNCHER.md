# FoxyPlayzZ Launcher

Android Minecraft Java launcher customization project based on the ZalithLauncher codebase.

## Target product

- Clean purple/neon gaming UI branded as **FoxyPlayzZ Launcher**
- Minecraft Java version management and downloads
- Microsoft account support
- Offline/local account support where supported by the base launcher
- Fabric, Forge and NeoForge workflows inherited from the base launcher
- Java runtime management inherited from the base launcher
- Touch controls, mod/resource-pack/file management and game launch pipeline inherited from the base launcher
- Android-first performance and storage-conscious packaging

## Repository strategy

The repository intentionally keeps large JRE/native payloads and generated APKs out of Git. Those artifacts should be produced by CI or distributed through Releases/LFS when required.

## Current state

The repository has been initialized and the project-management/build scaffolding is being added. The full uploaded ZalithLauncher archive is too large to be inserted as a single GitHub browser upload, so the source payload must be imported in a binary-safe way before claiming that the complete source tree is present.

## Important licensing note

ZalithLauncher remains the upstream project. Before distributing a customized build, preserve the upstream license and notices and comply with any applicable third-party component licenses.
