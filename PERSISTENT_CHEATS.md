# Persistent cheats fork

This fork changes the **Player** mod so that *Is invincible*, *Is invisible* and *Infinite ammo* are remembered in the SDK settings INI and re-applied automatically every time 47 spawns into a level (missions, restarts and Freelancer included).

A new checkbox, **Keep cheats on between missions**, turns the auto-apply on or off.

Every push builds the SDK on GitHub Actions and publishes `ZHMModSDK-Release.zip` as a GitHub release (tag `persistent-cheats-build-N`). Extract it into the game's `Retail` folder.
