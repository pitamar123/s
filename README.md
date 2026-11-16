# Starlane

A small space shooter that plays with a **keyboard** or a **touch screen**, packaged as an Android APK.

## Controls
- Keyboard: ← → or A / D to move, Space to fire, Enter to start
- Touch: drag to move, the ship fires while your finger is down

## Get the APK
1. Create a new GitHub repository and push this folder to the `main` branch.
2. Open the **Actions** tab and wait for **Build APK** to finish (about 5 minutes). You can also run it by hand with "Run workflow".
3. Open the finished run and download the `starlane-apk` artifact. Unzip it to get `app-debug.apk`.
4. Copy the APK to your phone and install it (allow "install unknown apps" when asked).

## Try it in a browser
Open `www/index.html` directly, or run `npx serve www`.

## Change the game
All game code is in `www/index.html`. Edit it, push, and the workflow builds a new APK.
