# EternalMists Boss Health

Releases of **Boss Health** (`BossHealth.dll`), a [Nexus](https://raidcore.gg/Nexus) addon for Guild Wars 2 that
gives the [Eternal Mists](https://eternalmists.app) addon the real health of the bosses it tracks (Greer, Decima, Ura
and the training golems).

## Warning: it reads the game's memory

Boss Health is code loaded into Guild Wars 2 that reads the game's memory to see the boss's health. It writes nothing
to the game and sends nothing over the network. ArenaNet has not approved it, and ArenaNet can suspend or ban accounts
that use third-party programs which read the game's memory. Use it at your own risk.

On first load it shows a disclaimer and reads nothing until you agree. You can withdraw in its options at any time;
the reads stop and it asks again on the next load.

## Install

Install it from the Nexus addon library, or download `BossHealth.dll` from [Releases](../../releases) and put it in
`<Guild Wars 2>/addons/`. Nexus updates it from the releases here. Check the download against the SHA-256 published
with each release.

After every Guild Wars 2 patch, Nexus disables Boss Health until a release for that patch is out.

The Eternal Mists addon works without Boss Health: it falls back to its own estimate of the boss's health, and never
reads the game's memory itself.

## Security

Report a security problem through GitHub's private vulnerability reporting on this repository (Security, then
"Report a vulnerability"), not in a public issue.

## License

[MIT](LICENSE).
