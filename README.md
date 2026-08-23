# Dodge

**Pet Dodgeball** — Multiplayer party dodgeball with desktop pets throwing harmless items.

Part of the [ComputerPets](https://github.com/RicheyWorks/computerpets) universe. Map: [computerpets-ecosystem](https://github.com/RicheyWorks/computerpets-ecosystem).

> Status: **design scaffold**. Gameplay contract is frozen. Engine choice is the one in the brief. Implementation comes next.

## Loop

Party night. No HP bars that threaten a lineage. Hit = sit emote. Visitation friends drop in. Steam lobby via Steamgate.

## Genre & engine

- Genre: **Party game**
- Engine: **Unity**
- Stack: Unity 6 · C# netcode · 4v4 throws · overlay sprites as bodies
- Default surface: `Unity editor`

## How you play

1. 4v4 arena. Throw food / toys, not weapons.
2. Last team standing or score.
3. OBS Overlay can show scores.
4. Host overlay can spectate as a giant sticker.

## Talks to

- computerpets-visitation
- computerpets-steamgate
- computerpets-twitch (bits = extra ball)
- computerpets-overlay

## Failure doctrine

Host migrate on drop. Grief throw at lobby → mute. Physics ragdoll off by default (reduce motion).

Canon rules that never yield:

- 210 living kinds. No illegal hybrids.
- Overlay pets can get tired, sick, or hide. Tokens are not burned by a minigame.
- Desktop walk stays the main quest. Closing Dodge must leave Rui walking.

## Layout

```
computerpets-dodge/
  README.md
  LICENSE
  docs/DESIGN.md
  src/                implementation lands here
```

## Run (Windows)

```powershell
Unity Hub > Dodge/; Netcode play mode. Steam appid via Steamgate.
```

Meet Rui first via the [flagship start-here](https://github.com/RicheyWorks/computerpets/blob/main/docs/START-HERE.md). This game is optional.

## License

MIT. See [LICENSE](LICENSE).

---

*Two hundred ten living kinds. Keep them so a line does not go quiet.*
