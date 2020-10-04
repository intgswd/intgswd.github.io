September was one of those months consumed by
## back-end upgrades.
Here's a quick recap of what happened.

### Object grabbing!
Originally my object collision system relied on the idea that every object occupied only one tile. When I realized you will eventually have to interact with a bed, which technically takes up six tiles, I realized I needed a robust system that would detect collisions for objects that occupy multiple tiles, including support for when they’re moving.

---

<video src="video/2020-09-10-object-grabbing.mp4" autoplay loop muted playsinline></video>

---

This quickly revealed to me that players had no idea what they were doing or what they "needed" to do. Since then I have been dedicating nearly all of my time to

A. learn, 

B. build a world and a system that will actually make sense, and

C. make it fun... At least for myself. Forget all you. I just want to drink a pixellated single-origin espresso.

---

<video src="video/2020-09-15-checkpoint-system.mp4" autoplay loop muted playsinline></video>

### Game-object-based checkpoint system for NPCs
This one was a nice refresh. Each checkpoint can contain a script that is automatically excecuted when the NPC reaches the checkpoint. The player can also interrupt the walking behaviour.

---

More to come soon!