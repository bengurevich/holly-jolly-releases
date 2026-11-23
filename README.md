# Holly Jolly Craft: launcher and packs

Holly Jolly Craft is a private, modded Minecraft: Java Edition server (1.21.1, Fabric) that a group of friends plays
on, with our own mods for winter games, basketball, chess, a gym and an in-game phone.

This repository is where the **Holly Jolly Launcher** and the modpack are published:

- **The launcher**: a small desktop app for Windows, macOS and Linux. It installs Minecraft 1.21.1, the Fabric mod
  loader and the right Java, keeps the modpack up to date with every release here (downloading only the files that
  changed), and starts the game, ready to play on the server.
- **The packs**: each release has a client pack and a server pack (`holly-jolly-craft-client-pack-<date>.zip`,
  `holly-jolly-craft-server-pack-<date>.zip`). The launcher always takes the newest.

## Signing in

The launcher signs players in with their own Microsoft account, through Microsoft's sign-in page (a code entered at
microsoft.com/link), only so they can play Minecraft with their own account and join the server. It never sees or
stores anyone's password: Microsoft gives it a sign-in token, kept only on that player's computer. Nothing is sent
anywhere but Microsoft, Xbox Live and Minecraft's own services.

## Downloads

The launcher and the packs are under [Releases](../../releases).


## Updates

New packs and launcher versions reach everyone at **6:00 AM New York time**, so a push in the middle of the day never
changes anyone's game or restarts the server mid-session. To send the newest pack out straight away, run the
**Release now** workflow (Actions tab > Release now > Run workflow). Launchers take it the next time they're
opened, and the server updater warns players and restarts onto it within about 15 minutes.
