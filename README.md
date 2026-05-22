# Scension-Game
# Team-Based Multiplayer Arena Prototype

A 5v5 competitive multiplayer game prototype built in Unreal Engine 5 using Lyra framework.

## 🧠 Overview
Players compete across multiple teams to progress through objectives and reach a final boss arena.

## ⚙️ My Contributions
- Implemented core gameplay systems using Lyra framework
- Built UI systems (minimap, player status, gold inventory, combat meter)
- Designed and integrated arena progression logic
- Worked on gameplay feedback systems and player state tracking

## 🎯 Key Features
- Multiplayer team-based structure
- Objective-driven match progression
- Dynamic UI with real-time player information
- Arena state transitions and reward cycles

## 🧩 Systems Built
- UI Layer (HUD, minimap, stats panels)
- Gameplay loop architecture
- Interaction systems for objectives and rewards

## 🎥 Examples

<br>
<br>
<br>
<br>





<!--                                          Directional UI and Map                                                                           -->


<h2>
  Directional UI and Map
</h2>
Developed a directional UI system that guides players toward active objectives in real time. Customized and expanded an existing minimap plugin to better fit the game’s design and gameplay needs, including implementing full map functionality and supporting logic.

<br>
<br>


https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/92549cde-0327-41d3-af2c-ee07aee9ed62

<br>
<br>

![Screenshot (384)](https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/2b73d985-ec01-4615-9838-c9c155518093)
![Screenshot (383)](https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/deb46fe9-4d7c-4b0c-bed0-d98b23532ef5)
![Screenshot (382)](https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/be22c5ab-bb24-4fe0-8003-10dec0cf9375)
![Screenshot (387)](https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/24711642-567c-4b77-b52a-0dc6e7801697)
![Screenshot (386)](https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/7921f994-c846-4301-b0ec-f3da176dbc84)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


<!--                                          Combat Meter                                                                          -->



<h2>
  Combat Meter
</h2>
Developed a combat status meter that informs players when they are out of combat. When the player takes damage, the progress meter resets and gradually refills until the player returns to a non-combat state. Also synchronized the health value displayed inside the UI circle with the player’s health bar, allowing players to view their exact remaining health in real time.


<br>
<br>

https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/a97c6c70-738a-4c4d-b173-0806d97945ef

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


<!--                                           Security System                                             -->



<h2>
  Security System
</h2>



Implemented a constructible security system that alerts teammates when enemies enter a controlled arena. Designed real-time UI indicators that immediately notify players when an enemy passes through the security gates, improving team awareness and defensive coordination.

<br>
<br>



https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/706e4b45-0de2-44db-a205-bde35cf4802f

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


<!--                                           Blessed Status/Teleporter Logic                                             -->




<h2>Blessed Status/Teleporter Logic</h2>

<br>
Implemented the “Blessed” status system, which grants players access to the boss arena and automatically teleports their entire team inside. Designed gameplay restrictions preventing players from using abilities while Blessed, with the status being removed upon death or downed state. Players obtain the status by reaching the Floating Island via the end-map teleporter and interacting with the fountain after paying 10,000 gold. Integrated the status with the UI so all players can track how many teammates are currently Blessed, and synchronized custom VFX created by the art team to visually represent the effect in-game.


<br>
<br>

<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/3940997f-634b-433f-b64e-cf1dc6c16d64" />

<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/c1bd575d-ed6d-4ea5-882a-50dd1decbf33" />



<br>
<br>

https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/4e264437-6db0-4cc6-8990-04e4980fd1db




<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>



<!--                                           Dragon Call                                             -->



<h2>Dragon Call</h2>

Implemented the Dragon Call event system, where activating a Dragon Call for 10,000 gold starts a two-minute countdown before a random dragon type spawns in the dragon pit. Designed territory-based information visibility so teams can only view dragon call timers and pit statuses for arenas they currently control. Added minimap proximity logic allowing allied players to temporarily see enemy dragon pit information when inside the pit’s circular minimap radius. Once the countdown expires, a random dragon remains active in the pit until defeated by a team. After slaying the dragon, the entire team receives a temporary power-up reward.

<br>
<br>

<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/cce952bd-47e2-4802-8ec0-14efd202a42c" />
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/9133e0fb-1bca-4e32-b499-52bc0c8efea1" />
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/8266da4e-347a-42a4-a295-1b58fb039f92" />
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/e683ad41-8c8c-4659-abb2-e3afff1f2ac1" />
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/45d7f938-d40d-4a44-a70c-caed1189d215" />
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/9e779204-2c03-4fe8-8ffc-ca73d98b884f" />








<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>



<!--                                          Neutral Rewards Logic                                             -->



<h2>Neutral Rewards Logic</h2>

<br>
Implemented the Neutral Reward system, where reward zones rotate continuously across four different sections throughout the match. Designed the gameplay logic so that, beginning 90 seconds into the match, reward zones labeled “#1” activate and spawn treasure chests at designated map locations. Any player from any team can capture the neutral reward, granting their entire team a large gold bonus. Developed the core systems for neutral reward timers, reward spawning behavior, and UI integration to keep players informed of active reward locations and timings.


<br>


https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/71516666-8549-4117-b0ca-bd8594eca1cf

<br>
<br>




