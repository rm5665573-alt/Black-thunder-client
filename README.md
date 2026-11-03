# BLACK THUNDER CLIENT — Fabric starter

Target: Minecraft Java 26.3, Fabric Loader 0.19.5.

## Build on GitHub using only your phone
1. Create a public or private repository named `black-thunder-client`.
2. Upload all files/folders from this ZIP, preserving their paths.
3. Open the repository's **Actions** tab.
4. Select **Build BLACK THUNDER** → **Run workflow** (or push to `main`).
5. Open the finished workflow run and download the `black-thunder-client-jar` artifact.
6. Extract the artifact ZIP; place the produced `.jar` in your MJ Launcher's Minecraft `mods` folder.

## Important
This is an initial source starter, not a prebuilt or tested JAR. GitHub Actions is where the first build will test compatibility. If the build fails, share the error log and the project can be corrected.

The GUI is a starter: Right Shift opens it, categories switch, and module rows toggle demo states. The module switches do not yet change gameplay. Gameplay-affecting modules must be implemented and tested individually; this starter does not bypass anti-cheat or provide anti-cheat evasion.
