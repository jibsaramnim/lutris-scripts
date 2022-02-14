# Lutris Game Installer Scripts

A small collection of Lutris game installer scripts I have created. All of these have been submitted to Lutris, they are only stored here for archival purposes and in case I need to update any of them.

# Submitted Installers

Here's a short list of game installers included in this repository. The easiest way to use them would be via the official Lutris website, but as installer submissions are manually reviewed, it can sometimes take quite a bit of time before they end up available through the site. In that case you can download any one of these and install them on your system by launching Lutris through the command line with the `-i` flag, like this: `lutris -i ~/Downloads/tortuga-two-treasures.yaml`.

## Tortuga: Two Treasures

Tortuga: Two Treasures is a pirate-themed action adventure game. Players take the role of Thomas "Hawk" Blythe, captain of the Hawkwind, his 18th century frigate.

- [Installer script](tortuga-two-treasures/tortuga-two-treasures.yaml).
- [On Lutris](https://lutris.net/games/tortuga-two-treasures/).
- Download available from [MyAbandonware](https://www.myabandonware.com/game/tortuga-two-treasures-fry).

## Sid Meier's Pirates!

Sail the Caribbean, marauding all on the high seas or ally your ship and crew as a privateer in search of riches - the life you choose is up to you. Face dogged enemies, raid unsuspecting villages, woo fair maidens, avoid capture or dig for buried treasure. Discover what it takes to become one of the most famous pirates in history!

- [Installer script](sid-meiers-pirates/sid-meiers-pirates-gog.yaml).
- [On Lutris](https://lutris.net/games/sid-meiers-pirates/).
- [Available on GoG](https://www.gog.com/game/sid_meiers_pirates).

## SimTown

![Submitted logo image](simtown/lutris-simtown-logo.jpg)

SimTown is one of several entries in the city-building simulation series, SimCity. As in prior installments, players are tasked as the mayor of a newly formed municipality, taking charge of it's expansion and success. Being aimed at a younger audience than that of the other games within the series a greater emphasis is placed on managing a small, socially ideal town than a sprawling metropolis. As such it features a much more stylized, cartoon representation and user interface, a number of added features allowing for greater interactivity with the populace, and a simplified system of resource management.

- [Installer script](simtown/simtown.yaml).
- [On Lutris](https://lutris.net/games/simtown/).
- Download available from [MyAbandonware](https://www.myabandonware.com/game/simtown-bc3).

## Stolen

![Submitted logo image](stolen/stolen-lutris-logo.png)

Stolen is a third-person stealth action game in which you play as a female thief. After your everyday job turns sour, you enter a web of conspiracy that threatens to destroy the entire city. With your stealth and agility, you'll break into and out of various locations (including museums, prisons, and satellite arrays) in an effort to steal priceless items. You'll have access to different high-tech gadgets and tools that will help you achieve your objectives.

- [Installer script](stolen/stolen.yaml).
- [On Lutris](https://lutris.net/games/stolen/).
- Download available from [MyAbandonware](https://www.myabandonware.com/game/stolen-fir).

## Prison Break: The Conspiracy

![Submitted logo image](prison-break-the-conspiracy/prison-break-conspiracy-lutris-logo.png)

Prison Break: The Conspiracy is an action-adventure video game based on the first season of the Fox television series Prison Break.

- [Installer script](prison-break-the-conspiracy/prison-break-the-conspiracy.yaml).
- [On Lutris](https://lutris.net/games/prison-break-the-conspiracy/).
- Download available from [MyAbandonware](https://www.myabandonware.com/game/prison-break-the-conspiracy-fji).

## Cemu

The well known Wii U emulator. Submitted an updated installation script which slightly tweaked the existing one like remove the version number from the installation path, so that there won't be a name mis-match with future Cemu updates. Also updated to the recent-most release as of 2022-02-14: Cemu v1.26.2d, with Cemuhook v0.5.7.6, and Graphics Pack v849.

- [Installer script](cemu/lutris-cemu.yaml).
- [On Lutris](https://lutris.net/games/cemu/).

---

# Draft Installers

Draft or work-in-progress installers that I have not yet submitted, either due to them not being finished, or due to technical limitations preventing the games from working as they should.

## Titanic: Adventure Out Of Time

Intrigue and adventure await you on board the Titanic, the most famous ocean liner in history. As a British secret agent on a vital mission, it is up to you to change the course of history as you explore the world’s most luxurious ocean vessel in all its original splendour.

**Note:** This game requires the display to be set to 256 colors and refuses to launch without passing this test. When using Xephyr to force this, the game's colors are all messed up, rendering the game unplayable. I have not yet found a solution to this problem, unfortunately.

- [Installer script draft](titanic-adventure-out-of-time/titanic-adventure-out-of-time-gog.yaml).
- [On Lutris](https://lutris.net/games/titanic-adventure-out-of-time/).
- [Available on GoG](https://www.gog.com/game/titanic_adventure_out_of_time).
