# Meveyk's Mods for Avatar: Frontiers of Pandora

Free mods for **Avatar: Frontiers of Pandora**, and the program that looks after them. This page is where they are
released. You install only the mods you want; each one works on its own. More mods will be added here.

**Status:** in development. There is no release yet; the first one appears on the Releases page when the mods are
polished.

## The mods

| Mod | What it adds | Download |
|---|---|---|
| **Meveyk Core** | The foundation. Every mod needs it. | `MeveykCore.zip` |
| **Meveyk's Posing & Creative Suite** | Pose the character by hand in photo mode: grab an arm, a leg, the head or a finger and move it. Save poses, play motions, change the character's look, place objects, take large pictures. | `Meveyk-PosingCreativeSuite.zip` |
| **Meveyk's Create a Campfire Mod** | Build a campfire anywhere, rest or sleep at it, let time pass, stomp it out. | `Meveyk-CreateACampfire.zip` |
| **Meveyk's Immersive Tablet Mod** | The on-screen display moves onto a tablet the character holds: compass, objective, scanner, Hunter's Guide. | `Meveyk-ImmersiveTablet.zip` |
| **Meveyk's Aim Mod** | Raise the rifle to the eye and aim down its sights. | `Meveyk-Aim.zip` |
| **Meveyk's Mod Manager, online edition** | Optional. Replaces the offline Mod Manager that comes with the Posing & Creative Suite. | `Meveyk-ModManager-Online.zip` |

All downloads are on the [Releases](../../releases) page. The newest release lists every mod with its version; a
release that changes one mod holds only that mod's zip.

## Install

1. Install the **Universal Snowdrop Modloader** by Patrick Mollohan from its Nexus Mods page. It is not included
   here.
2. Unzip **MeveykCore.zip** into the game folder (the folder with `afop.exe`).
3. Unzip the zip of every mod you want into the same folder.
4. Start the game. The mods' settings are in one window.

Later you can install and update through **Meveyk's Mod Manager** (it comes with the Posing & Creative Suite):
**Mods > Install a mod**, or drop a zip on that page. It reads the version inside the zip and does not put an older
version over a newer one unless you say so.

## Meveyk's Mod Manager: two editions

| | Offline edition | Online edition |
|---|---|---|
| Where | inside the Posing & Creative Suite, here and on Nexus Mods | here only: `Meveyk-ModManager-Online.zip` |
| Internet | never connects | see below |
| Updates | you install a newer zip yourself | an Update button on each mod that has a newer release here |
| Community (packs shared between players) | not in the program | browse, get, like, comment, share your own |

The offline edition is complete: nothing in it waits for the other one.

**What the online edition sends, and when.**
- **Updates:** when its Mods page is first shown, and then at most every three hours, it downloads one small list
  (`versions.json`) from this page's newest release. Nothing about you or your PC is sent. A mod is downloaded only
  when you press Update, the file is checked against the list, and you can undo the install.
- **Community:** when you open the Community tab it asks the Community server for the list of packs. Sharing and
  comments need a sign-in with Discord: the server then keeps your Discord name and id, and what you share. The
  rules and what is kept about you are shown before your first share.

## Check a download

Every release lists the SHA-256 of each zip. To check a file you downloaded, in PowerShell:

```powershell
Get-FileHash .\Meveyk-PosingCreativeSuite.zip -Algorithm SHA256
```

The mods are the same files here and on Nexus Mods.

## Source code

The source is not public at this time. The downloads contain no game files.

## Credits

The mods run on the Universal Snowdrop Modloader by Patrick Mollohan. The in-game overlay uses Dear ImGui (Omar
Cornut, MIT) and MinHook (Tsuda Kageyu, BSD 2-clause). The Mod Manager is drawn with egui. Full credits are in
`CREDITS.txt` inside `MeveykCore.zip`.

Avatar: Frontiers of Pandora is (c) Ubisoft and 20th Century Studios. These mods are made by fans and are not
affiliated with them.
