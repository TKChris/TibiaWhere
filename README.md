# TibiaHunt — Monster Spawn Finder

A fan-made interactive map for finding monster spawn locations in Tibia.

## Features
- Search for monsters in the Beginner Weekly tasks by name
- Click a spawn entry to jump to the exact location on the map
- Coordinate data sourced from TibiaWiki

## How to add a monster
Open `monsters.json` and follow this pattern:

```json
{ "name": "Crab", "image": "/images/Crab.gif", "loot": [], "spawns": [
    { "x": 32138, "y": 32560, "floor": 7, "label": "Goroma Beach", "note": "Goroma before the underground passage onto the vulcano" },
    { "x": 32389, "y": 32943, "floor": 7, "label": "Shattered Isles", "note": "Access is gained through The Shattered Isles Quest" }
  ]
}
```

## Credits
- Map tiles: TibiaMaps.io
- Spawn data: TibiaWiki
- Not affiliated with CipSoft