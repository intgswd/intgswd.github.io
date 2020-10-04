September was one of those months consumed by a slew of back-end upgrades.
Here's a quick recap of what happened.

---

## Object grabbing!
Originally my object collision system relied on the idea that every object occupied only one tile. When I realized you will eventually have to interact with a bed, which technically takes up six tiles, I realized I needed a robust system that would detect collisions for objects that occupy multiple tiles, including support for when they’re moving.

---

<video src="video/2020-09-10-object-grabbing.mp4" autoplay loop muted playsinline></video>

---

## Game-object-based checkpoint system for NPCs
This one was a nice refresh. Each checkpoint can contain a script that is automatically excecuted when the NPC reaches the checkpoint. The player can also interrupt the walking behaviour.

---

<video src="video/2020-09-15-checkpoint-system.mp4" autoplay loop muted playsinline></video>

---

More to come soon!