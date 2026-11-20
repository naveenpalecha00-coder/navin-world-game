NAVIN WORLD — FULL GAME DEVELOPMENT PROMPT PACK
Version: 2.0
Owner / creator credit requested: Navin Palecha

PURPOSE
This pack is a structured set of detailed prompts and technical specifications for planning and building one complete open-world game project for Android and Windows PC. It is intended to be supplied to Lovable, Unreal Engine developers, coding agents, and GitHub workflows as appropriate.

IMPORTANT REALITY CHECK
This ZIP contains text specifications and prompts, not a finished game, Unreal Engine project binaries, 3D models, animations, sounds, maps, APK, or EXE. A text-only ZIP does not become a 1 GB game merely because the planned game is large. A real high-fidelity game requires a large amount of original/licensed assets, engine project files, implementation, builds, and device testing. The ZIP is intentionally compact and can be expanded as development produces real assets.

CORE RULE
Do not claim a feature is implemented until it exists in the game, is connected to gameplay, and has passed its stated test. Do not use fake buttons, placeholder screenshots, simulated download links, or pretend build-success messages.

PROJECT VISION
Create NAVIN WORLD: a fictional, original, photorealistic open-world life-and-crime action game inspired by the broad genre of modern open-world games. Do not copy GTA 6 maps, characters, missions, logos, dialogue, UI, music, assets, or proprietary designs. Create original locations, story, characters, brands, vehicles, and missions.

TARGETS
- Android APK for supported Android devices.
- Windows PC build (installer or packaged EXE folder; use an installer only when configured).
- Shared gameplay design and save format where practical.
- Separate graphics presets and input systems for mobile and PC.
- Full-world design target, built and validated through staged production milestones. Staged development is an internal production method, not a decision to ship a tiny demo.

SUGGESTED ENGINE
Unreal Engine 5, subject to verifying the selected UE version's Android/Windows support, licensing, hardware needs, plugins, and build pipeline before production.

HOW TO USE
1. Read this file and 01_MASTER_PROJECT_PROMPT.txt first.
2. Give 02_LOVABLE_DASHBOARD_PROMPT.txt to Lovable. Lovable should build the project-management/dashboard website, not pretend to generate a complete Unreal game.
3. Use 03_UNREAL_PROJECT_ARCHITECTURE.txt and the feature prompts as the implementation specification for Unreal Engine.
4. Use the GitHub and CI prompts for source control and build automation.
5. Keep a feature status ledger: PLANNED / IN DEVELOPMENT / IMPLEMENTED / TESTED / RELEASED.
6. Never mark a feature TESTED without recorded test evidence.

RECOMMENDED REPOSITORY
navin-world-game/
  Game/                 Unreal project and source-controlled game code
  Config/
  Content/              Only assets that are legally usable and appropriately sized
  Plugins/
  BuildScripts/
  Tests/
  Docs/                 This prompt pack and design documentation
  .github/workflows/    Windows and Android build workflows
  README.md

ASSET POLICY
Use original assets, properly licensed marketplace assets, or clearly documented open-license assets. Track asset source, license, author, and redistribution permissions. Do not scrape or redistribute copyrighted game assets.

PERFORMANCE POLICY
Do not promise GTA 6-level visuals on every phone. Use scalable quality settings, device capability detection, dynamic resolution where appropriate, LODs, HLODs, occlusion culling, texture streaming, level/world streaming, and tested performance budgets. State exact tested device models and measured frame rates in release notes.

SECURITY POLICY
Never store signing keys, passwords, API tokens, or certificates in Git. Use GitHub Actions secrets or a secure signing service. Do not put private keys in the Lovable frontend or public repository.

DELIVERY DEFINITION
A release is complete only when:
- Android APK installs, launches, saves, loads, and passes the required device test matrix.
- Windows build installs/runs, saves/loads, and passes the required PC test matrix.
- All advertised features are implemented and tested.
- Known limitations are disclosed.
- Release assets have checksums and version notes.
