# Pic2Pet Releases

Public release channel for Pic2Pet installers, update manifests, and release notes.

The private source code lives in the `Pic2Pet` repository. This repository should
not contain source code or private app data.

## Current Beta

- Version: `0.1.0-beta`
- macOS Intel: `Pic2Pet_0.1.0_macOS_x64.zip`
- macOS Apple Silicon: `Pic2Pet_0.1.0_macOS_arm64.zip`
- Windows: `Pic2Pet_0.1.0_Windows_x64-setup.exe`

## Release Asset Policy

Upload app packages as GitHub Release assets. Keep local staging files in
`downloads/`; they are ignored by Git so the repository history stays light.

For each release, publish:

```text
Pic2Pet_0.1.0_macOS_x64.zip
Pic2Pet_0.1.0_macOS_arm64.zip
Pic2Pet_0.1.0_Windows_x64-setup.exe
release.json
```

Later, when Tauri auto-update is enabled, also publish the signed updater
artifacts and the updater manifest required by Tauri.
