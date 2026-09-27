# Suzuka's impact gas grenade v1.6.0

Changes the G-16 impact grenade to release the G-4 gas payload on contact while preserving impact detonation. Requires Bingus Shared Loader v15+ (API 1).

Disable earlier G-16 Gas Impact packages before installing this release. The mod checks the original component record before writing, verifies the result, and attempts to restore the change on shutdown. Runtime checks are paced to reduce stutter.

Log: `%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs\SuzukaImpactGasGrenade.log`. Offline runtime and package tests passed; in-game performance after respawn and mission transitions remains unverified.
