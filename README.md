# Jordon Plays Client

A Fabric client mod project for Minecraft Java Edition 1.21.1, built with Java 21.

## Features
- Custom dark Click GUI with purple/blue accents
- Right Shift opens the interface
- Toggleable client utility module list
- Module toggles persist in `config/jordonplaysclient.properties`
- GitHub Actions build workflow

## Build on GitHub
1. Upload the contents of this ZIP into your repository (not the ZIP itself).
2. Ensure the repository default branch is `main` or `master`.
3. Open the **Actions** tab and select **Build Jordon Plays Client**.
4. Wait for the workflow to finish successfully.
5. Open the completed workflow run and download the artifact named `jordon-plays-client-0.2.0`.
6. The mod JAR is inside that artifact.

## Build locally
Requires Java 21 and Gradle:
```bash
gradle build
```
The compiled JAR will be in `build/libs/`.

## Install
Put the built JAR into the Minecraft `mods` folder in a Fabric 1.21.1 installation with Fabric API installed.

This starter version focuses on the client GUI and saved module toggles. Module entries are UI toggles and do not yet implement each feature's visual behavior.
