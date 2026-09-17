# RUNAWAY.EXE

**RUNAWAY.EXE** is a story-driven horror add-on for **Minecraft Bedrock Edition**.

It is designed as a **standalone add-on**, not a prebuilt `.mcworld`. The goal is for players to activate the Behavior Pack and Resource Pack in a normal Minecraft world and gradually encounter the horror story through scripted events, structures, entities, sounds, portals, and exploration.

---

## Story

Four friends — **Eli, Maya, Noah, and Lucas** — travel to an abandoned mining town after hearing about a strange radio transmission that has been broadcasting from the area every night for more than twenty years.

The message is always the same:

> **“If you can hear this, do not come looking for us.”**

Nobody knows who recorded it.

The group decides to investigate.

### Chapter 1 — The Empty Town

The group arrives shortly before sunset.

The town looks completely abandoned. Cars are rusting in the streets, houses have been left open, and personal belongings are still sitting where their owners left them.

There are no villagers.

No animals.

At first, there are not even hostile mobs.

Inside an old security office, the group finds documents describing an underground mining project known as **Project Hollow**.

The final page contains one sentence:

> **“We found something below the bedrock.”**

That night, an old radio suddenly switches on.

A distorted voice says:

> **“Five people entered the town.”**

There are only four friends and the player.

Then footsteps begin outside.

---

### Chapter 2 — Beneath the Mine

The group discovers a hidden elevator inside the abandoned mine.

It should only descend a short distance.

Instead, it keeps going.

When the doors finally open, they reveal a massive underground research facility covered in strange black material.

At the center of the facility is an object the researchers called:

## The Door

It looks like a rectangular opening made from absolute darkness.

Nothing can break it.

Nothing can pass through it.

Until the player approaches.

The Door opens.

Something pulls the entire group inside.

---

### Chapter 3 — The Other Side

The player wakes up alone.

The new place resembles the Overworld, but everything is wrong.

Trees grow in impossible directions.

The sky is completely black.

Buildings from the abandoned town appear in places where they should not exist.

Hallways repeat.

Rooms change when the player looks away.

Sometimes the player finds perfect copies of places they visited earlier, except small details are different.

Eventually, the player finds Maya.

She says she has been looking for everyone.

But she begins asking strange questions.

> **“Do you remember which one of us entered first?”**

> **“Do you remember what my face looked like?”**

Then the player's radio activates.

The real Maya is on the other end.

The person standing beside the player is not Maya.

---

## The Mimics

Creatures inside the dimension cannot create their own identities.

Instead, they copy people.

At first, their disguises are imperfect.

They stand too still.

Their heads move incorrectly.

They repeat sentences.

They stare at the player for too long.

But the longer they observe someone, the better they become.

Eventually, a Mimic can imitate:

- appearance
- movement
- footsteps
- equipment
- names
- prerecorded character voices
- behavior patterns

The only reliable weakness is memory.

A Mimic cannot correctly remember an event it never witnessed.

That becomes one of the main mechanics of the story.

---

### Chapter 4 — Missing

The group slowly reunites.

Eli.

Maya.

Noah.

But Lucas is missing.

His radio signal leads the others into a massive structure filled with rooms copied from their memories.

Eventually, the player finds Lucas trapped behind glass.

He begs to be released.

Then another Lucas appears.

Both claim the other is the Mimic.

The player has to decide who to trust.

That decision permanently affects the rest of the story.

---

## The Observer

The Mimics are not the true threat.

Something else controls the dimension.

The original researchers called it:

# The Observer

The Observer watches people.

It studies their memories.

It reconstructs places they remember.

It creates Mimics to understand human behavior.

The abandoned town was not simply destroyed.

Many of its inhabitants were copied.

The real people may still be trapped somewhere inside the Other Side.

The radio transmission from twenty years ago was not sent from the town.

It was sent from inside The Door.

---

### Chapter 5 — Don't Look Away

The Observer finally begins hunting the player.

Most of the time, the player never sees its entire body.

Only pieces of it appear:

- a silhouette at the end of a hallway
- a hand disappearing behind a doorway
- eyes between trees
- a shadow behind another character
- footsteps that stop whenever the player turns around

Eventually, the player discovers its rule:

> **The Observer moves when nobody is looking at it.**

Looking away lets it approach.

Looking back makes it stop.

But staring at it for too long begins to distort the player's vision.

The player eventually has no choice but to run.

---

### Chapter 6 — The Way Home

The group discovers another Door.

It may lead back to the normal world, but it no longer has power.

To activate it, the player must restore several systems scattered across the dimension.

Each system is located in a major horror area.

### The Hospital

An abandoned hospital that endlessly rearranges itself.

Something moves through the vents.

### The Forest

A dark forest where voices imitate the player's friends.

### The Flooded Facility

A research complex slowly filling with water.

### The Memory Town

A perfect recreation of the abandoned town from before everyone disappeared.

Each completed location weakens the Observer.

But every encounter also gives the Mimics more information about the group.

---

# Endings

Player decisions determine who survives and what returns through The Door.

## Escape

The survivors reach the portal and escape.

Everything appears normal.

Then the radio activates one final time.

> **“You forgot someone.”**

## The Mimic

The player trusted the wrong person.

Everyone appears to escape safely.

Days later, the real missing friend contacts the player.

Something else came home instead.

## The Observer

If the player discovers enough hidden research, they learn how to permanently close The Door.

Someone must stay behind to activate the system.

Years later, another group enters the abandoned mine.

They find an old radio.

It turns on.

> **“If you can hear this, do not come looking for us.”**

The story returns to the beginning.

---

# Main Entities

### The Mimic
Copies story characters and gradually becomes more convincing.

### The Watcher
Observes the player from distant locations and disappears when approached.

### Crawlers
Failed copies that move through vents, ceilings, tunnels, and maintenance areas.

### The Lost
People who have been trapped inside the Other Side for years.

### The Observer
The main antagonist and intelligence controlling the dimension.

---

# Add-on Design

RUNAWAY.EXE is intended to work inside a normal Minecraft Bedrock world.

The player should not need to download a dedicated adventure map.

Planned systems include:

- Behavior Pack + Resource Pack
- Minecraft Script API
- story progression and persistent choices
- custom entities and animations
- custom sounds and radio transmissions
- generated or placed story structures
- portal sequences
- horror encounters
- scripted chase scenes
- camera effects and cutscenes
- environmental puzzles
- Mimic identity mechanics
- Observer line-of-sight behavior
- multiplayer-aware story logic
- multiple endings
- a separate horror dimension where supported

---

# Story Activation

The horror should not begin immediately when the add-on is enabled.

A normal Minecraft world can remain normal until the player discovers or repairs a **Broken Radio**.

Example progression:

```text
Normal survival
      ↓
Find the Broken Radio
      ↓
Repair it
      ↓
Hear strange broadcasts
      ↓
Receive coordinates
      ↓
Find the abandoned building / mine
      ↓
Discover Project Hollow
      ↓
Open The Door
      ↓
Enter the Other Side
      ↓
Survive
```

This lets RUNAWAY.EXE behave like an actual add-on rather than a disguised adventure map.

---

# Development Status

**Early development / concept stage.**

The story and core gameplay direction are currently being designed before the complete Bedrock implementation is built.

---

## Platform

- **Minecraft:** Bedrock Edition
- **Format:** Add-on (`.mcaddon`)
- **World required:** No custom `.mcworld`
- **Primary technologies:** Behavior Pack, Resource Pack, Script API

---

# RUN.

You opened The Door.

Now it knows where you live.
