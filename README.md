# Lutris Game Installer Scripts

A small collection of Lutris game installer scripts I have created. All of these have been submitted to Lutris, they are only stored here for archival purposes and in case I need to update any of them.

# Submitted Installers & Installer updates

Here's a short list of game installers included in this repository. The easiest way to use them would be via the official Lutris website, but as installer submissions are manually reviewed, it can sometimes take quite a bit of time before they end up available through the site. In that case you can download any one of these and install them on your system by using the "Install from a local install script" option in Lutris (introduced in v0.5.10), or by launching Lutris through the command line with the `-i` flag, like so: `lutris -i ~/Downloads/tortuga-two-treasures.yaml`.

## Minecraft: Java Edition

MultiMC is a free, open source launcher for Minecraft, managed by @peterixxx and @02JanDal. It allows you to have multiple, separate instances of Minecraft (each with their own mods, texture packs, saves, etc) and helps you manage them and their associated options with a simple interface.https://multimc.org/

### Update notes

- Updated installer scripts to be compatible with more recent versions of Lutris.

### Links

    - [Installer script](minecraft/minecraft-multimc.yaml)
    - [On Lutris](https://lutris.net/games/minecraft/)

## Star Wars Galaxies: An Empire Divided

Star Wars Galaxies Legends client will be installed. The client will allow downloading all of the necessary game files. The server is based on the New Game Enhancement (NGE) era of Star Wars Galaxies including all of the expansions (even Jump to Lightspeed).

### Update notes

    - Added specific wine runner version, as the launcher crashes with newer versions.
    - Added specific DXVK version, as there are graphical issues with newer versions
    - Added dgVoodoo's ddraw dll to fix the game not wanting to launch
    - Added font smoothing fix to make game and launcher text legible.
    - Added prefix and working dir.

### Version history

    - **2022-04-18:** Updated script to make use of Lutris v0.5.10's new built-in dgVoodoo2 support.
    - **2022-03-08:** Submitted installer requiring a manually downloaded dgVoodoo zip file.

### Links

    - [Installer script](star-wars-galaxies-an-empire-divided/swg-legends.yaml)
    - [On Lutris](https://lutris.net/games/star-wars-galaxies-an-empire-divided/)

## Cemu

Experimental software to emulate Wii U applications on PC.

### Update notes

    - Updated installation path to be future-proof (Removed version from path)
    - Updated to Cemu 1.26.2f
    - Updated Cemuhook to v0.5.7.6
    - Updated GraphicsPack to v849

### Links

    - [Installer script](cemu/lutris-cemu.yaml)
    - [On Lutris](https://lutris.net/games/cemu/)

## Prison Break: The Conspiracy

![Submitted logo image](prison-break-the-conspiracy/prison-break-conspiracy-lutris-logo.png)

Prison Break: The Conspiracy is an action-adventure video game based on the first season of the Fox television series Prison Break.

### Links

    - [Installer script](prison-break-the-conspiracy/prison-break-the-conspiracy.yaml)
    - [On Lutris](https://lutris.net/games/prison-break-the-conspiracy/)

- Download available from [MyAbandonware](https://www.myabandonware.com/game/prison-break-the-conspiracy-fji)

## Stolen

![Submitted logo image](stolen/stolen-lutris-logo.png)

Stolen is a third-person stealth action game in which you play as a female thief. After your everyday job turns sour, you enter a web of conspiracy that threatens to destroy the entire city. With your stealth and agility, you'll break into and out of various locations (including museums, prisons, and satellite arrays) in an effort to steal priceless items. You'll have access to different high-tech gadgets and tools that will help you achieve your objectives.

### Links

    - [Installer script](stolen/stolen.yaml)
    - [On Lutris](https://lutris.net/games/stolen/)
    - Download available from [MyAbandonware](https://www.myabandonware.com/game/stolen-fir)

## SimTown

![Submitted logo image](simtown/lutris-simtown-logo.jpg)

SimTown is one of several entries in the city-building simulation series, SimCity. As in prior installments, players are tasked as the mayor of a newly formed municipality, taking charge of it's expansion and success. Being aimed at a younger audience than that of the other games within the series a greater emphasis is placed on managing a small, socially ideal town than a sprawling metropolis. As such it features a much more stylized, cartoon representation and user interface, a number of added features allowing for greater interactivity with the populace, and a simplified system of resource management.

### Links

    - [Installer script](simtown/simtown.yaml)
    - [On Lutris](https://lutris.net/games/simtown/)
    - Download available from [MyAbandonware](https://www.myabandonware.com/game/simtown-bc3)

## Sid Meier's Pirates!

Sail the Caribbean, marauding all on the high seas or ally your ship and crew as a privateer in search of riches - the life you choose is up to you. Face dogged enemies, raid unsuspecting villages, woo fair maidens, avoid capture or dig for buried treasure. Discover what it takes to become one of the most famous pirates in history!

### Links

    - [Installer script](sid-meiers-pirates/sid-meiers-pirates-gog.yaml)
    - [On Lutris](https://lutris.net/games/sid-meiers-pirates/)
    - [Available on GoG](https://www.gog.com/game/sid_meiers_pirates)

## Tortuga: Two Treasures

Tortuga: Two Treasures is a pirate-themed action adventure game. Players take the role of Thomas "Hawk" Blythe, captain of the Hawkwind, his 18th century frigate.

### Links

    - [Installer script](tortuga-two-treasures/tortuga-two-treasures.yaml)
    - [On Lutris](https://lutris.net/games/tortuga-two-treasures/)
    - Download available from [MyAbandonware](https://www.myabandonware.com/game/tortuga-two-treasures-fry)

---

# Draft Installers

Draft or work-in-progress installers that I have not yet submitted, either due to them not being finished, or due to technical limitations preventing the games from working as they should.

## Titanic: Adventure Out Of Time

Intrigue and adventure await you on board the Titanic, the most famous ocean liner in history. As a British secret agent on a vital mission, it is up to you to change the course of history as you explore the world’s most luxurious ocean vessel in all its original splendour.

**Note:** This game requires the display to be set to 256 colors and refuses to launch without passing this test. When using Xephyr to force this, the game's colors are all messed up, rendering the game unplayable. I have not yet found a solution to this problem, unfortunately.

### Links

- [Installer script draft](titanic-adventure-out-of-time/titanic-adventure-out-of-time-gog.yaml)
- [On Lutris](https://lutris.net/games/titanic-adventure-out-of-time/)
- [Available on GoG](https://www.gog.com/game/titanic_adventure_out_of_time)
