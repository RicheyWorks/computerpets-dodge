# Dodge design

Implement against this file, not folklore.

## Identity

- Product: **Dodge**
- Repo: `computerpets-dodge`
- Idea: Pet Dodgeball
- Genre: Party game
- Engine: Unity
- Surface: `Unity editor`

## Loop

Party night. No HP bars that threaten a lineage. Hit = sit emote. Visitation friends drop in. Steam lobby via Steamgate.

## Play beats

- 4v4 arena. Throw food / toys, not weapons.
- Last team standing or score.
- OBS Overlay can show scores.
- Host overlay can spectate as a giant sticker.

## Neighbors

- computerpets-visitation
- computerpets-steamgate
- computerpets-twitch (bits = extra ball)
- computerpets-overlay

## Failure doctrine

Host migrate on drop. Grief throw at lobby → mute. Physics ragdoll off by default (reduce motion).

## Hard rules

1. Minigames cannot mint or burn NFTs by themselves (Minter is the write path).
2. Stats come from lived overlay care + Dojo caps, not cash shop.
3. Species kits stay inside Lore. Illegal hybrids never spawn.
4. Fail soft: the desktop overlay process is not this process.
