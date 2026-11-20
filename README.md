# Kitty Client (Fabric, Minecraft 1.21.1)

Client-side HUD mod: FPS, coordinates, keystrokes, module list. Config: `.minecraft/config/kitty-client.properties`.
Default keys (rebind in Controls > Kitty Client): Numpad 1-4 toggle FPS, coords, keystrokes, module list.

## Build
1. Install JDK 21 and Gradle 8.8 or newer.
2. Check the four version lines in gradle.properties against https://fabricmc.net/develop (1.21.1).
3. In this folder run: `gradle wrapper --gradle-version 8.10` then `./gradlew build` (Windows: `gradlew.bat build`).
4. Jar: `build/libs/kitty-client-0.1.0.jar`. Put it in `mods/` together with Fabric API.
