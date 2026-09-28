# FoxyPlayzZ Launcher

An Android-first Minecraft Java launcher customization project targeting a clean, fast and modern FoxyPlayzZ experience.

## Planned / inherited launcher capabilities

- Minecraft Java version management and downloads
- Microsoft account flow
- Offline/local account flow where supported by the upstream launcher
- Fabric, Forge and NeoForge workflows
- Java runtime management
- Touch controls and controller-friendly Android interaction
- Mod, resource-pack and game-file management
- Clean FoxyPlayzZ purple/neon visual identity
- CI-built debug APK artifacts
- Binary-safe repository layout; large runtimes are kept out of Git

## Build

The repository includes a GitHub Actions workflow under `.github/workflows/upstream-build.yml`. Run it from **Actions → FoxyPlayzZ Launcher - upstream build**, choose the desired ZalithLauncher branch/tag/commit, and the workflow will prepare a branded build and publish the debug APK as an Actions artifact.

## Source status

The GitHub repository has been initialized with the FoxyPlayzZ project specification, Git hygiene and automated build/import workflow. The original uploaded ZalithLauncher archive is large and contains runtime/native payloads that should not be committed directly to GitHub. The workflow therefore obtains the upstream source during CI instead of pretending the complete archive has already been committed.

## Upstream and licensing

This project is a customization workflow around ZalithLauncher. Keep the upstream license, copyright notices and third-party licenses intact when redistributing builds.
