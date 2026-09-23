# Pioneer Pipelines 1.0.1

- Fixed Pioneer pipeline capacities being reduced to 150 m³/min in the tested Satisfactory Plus setup. Mk.3, Mk.4 and Mk.5 now restore their intended limits of 750, 900 and 1,200 m³/min when loaded or built.
- Added the Pioneer Cross Junction 1200: a four-way junction supporting up to 1,200 m³/min.
- Renamed the existing junction to Pioneer T-Junction 1200 to clearly distinguish both variants.
- Added the four-way junction to the Advanced Fluid Transport milestone. Existing saves with the milestone or legacy Pioneer junction unlocked receive the new recipe automatically.
- Kept the diagnostic test sink disabled and excluded from normal progression and the build menu. Existing test-sink actors remain loadable and dismantleable without destroying fluid.
- Preserved existing building asset paths for save compatibility.

## Installation

Install version 1.0.1 on both clients and dedicated servers, then restart the game and server.

## Validation scope

The supplied Satisfactory Plus network captures confirm restored 1,200 m³/min limits for Mk.5 pipes and pumps, and a working four-way junction with all four ports connected. Sustained full-capacity throughput and the new changes on a Linux dedicated server have not yet been verified by these captures.

---

# Änderige

## 1.0.0-rc.2

- Test-Sink us de Freischaltige und de Produzente vom Baurezäpt entfernt.
- Bereits freigschaltets Sink-Rezept wird uf em Host bim Weltstart entfernt.
- Flüssigkeitsvernichtig vo alte Test-Sinks deaktiviert; alti Actors blibed ladbar.
- GitHub-Dokumentation, statischi Siite, Modpage und Bilder ergänzt.

No z’teste: Sink-Migration im alte Save, Client/Server-Neustart und d’offeni Wandmontage.

## Bisherige Release-Kandidat

- Rohrstufe 750 / 900 / 1200 m³/min.
- 1200er-Pumpe mit Vanilla-Förderhöchi und Animatione.
- Ventil mit Drosselig, persistenter Istellig und korrigierter Multiplayer-Azeig.
- 1200er-Wasserextraktor und Rohrchrüzig.
- Reguläri Meilestei mit sichtbare Belohnige und eigene Icons.
- Linux-Dedicated-Server erfolgreich im Spiel testet.
