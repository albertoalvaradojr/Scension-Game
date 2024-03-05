# Scension-Game
Created using Unreal Engine 5 and Lyra's Plugin.
<br>
<br>
In charge of Implementing UI and core gameplay mechanics. Some examples can be seen below including the minimap, players in your team (left side), player stats (top right corner), arena status (top next to minimap) Gold inventory, abilities and combat meter.


![Screenshot (369)](https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/a14dbee3-0a36-453c-91bb-356ef0a401cb)


<h2>
  Directional UI and Map
</h2>
Developed a Directional UI element that directs the player to where the Objective is. As well, modified a MiniMap plugin and made it my own. Also, added a Fullmap Logic.

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
<h2>
  Combat Meter
</h2>
Combat meter that lets the player know when the player is free of combat. Once he is damaged the progess meter goes to zero and slowly increases until it reaches the no combat status. As well, the Health number inside the circle is synced with the health bar the the player can know exactly how much health they have.

<br>
<br>

https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/a97c6c70-738a-4c4d-b173-0806d97945ef

<br>
<br>

<h2>
  Security System
</h2>



Security system that you can construct that lets your team know when an enemy has entered your controlling arena. UI Indicators will let you know the second the enemy passes the security gates.

<br>
<br>



https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/706e4b45-0de2-44db-a205-bde35cf4802f

<br>
<br>

<h2>Blessed Status/Teleporter Logic</h2>

<br>
Blessed Status allows player to enter the Boss arena and automatically teleports their team inside. You cannot use abilities while Blessed and once you die or get downed, the status goes away. Players can only get the status by taking the Teleporter at the end of the map to the Floating Island(Cost 10,000 gold) and then drink from the founatin. I synced the status to the UI and added in A VFX that was created by one of the artist of the team. All players will know how many players are blessed.

<br>
<br>

<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/3940997f-634b-433f-b64e-cf1dc6c16d64" width="500" height="300"/>

<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/c1bd575d-ed6d-4ea5-882a-50dd1decbf33" width="500" height="300"/>





https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/4e264437-6db0-4cc6-8990-04e4980fd1db




<br>
<br>

<h2>Dragon Call</h2>


<br>
When a dragon call is made, a 2 minute timer begins counting down. Teams only retain the information of the dragon call timers and the dragon pit statuses to arena’s that their team controls.
When within the circular minimap radius of enemy dragon pits, the dragon-pit information is visible to all allies, but only while remaining inside of the circular minimap radius.
When the 2 minute dragon timer has elapsed a random dragon of the multiple different types will arrive in the pit and stay in the dragon pit until any team has slain the dragon.
To activate the Dragon Call, 10,000 gold is required. After Defeating the dragon, the whole team recieves a power up.

<br>
<br>

<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/cce952bd-47e2-4802-8ec0-14efd202a42c" width = "500" height="375"/>
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/9133e0fb-1bca-4e32-b499-52bc0c8efea1" width = "500" height="375"/>
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/8266da4e-347a-42a4-a295-1b58fb039f92" width = "500" height="375"/>
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/e683ad41-8c8c-4659-abb2-e3afff1f2ac1" width = "500" height="375"/>
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/45d7f938-d40d-4a44-a70c-caed1189d215" width = "500" height="375"/>
<img src="https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/9e779204-2c03-4fe8-8ffc-ca73d98b884f" width = "500" height="375"/>








<br>
<br>

<h2>Neutral Rewards Logic</h2>

<br>
Neutral rewards are released in 4 sections that are continuously cycled throughout the entire match. Starting at 90 seconds into the match the reward zones labeled #1 will activate(releasing a treasure chest) at the marked location, allowing any player from any team to collect the neutral reward, rewarding their entire team with massive amounts of gold. I implemented the logic behind the Neutral Reward Timers,spawning, and UI for the rewards.

<br>


https://github.com/albertoalvaradojr/Scension-Game/assets/65637580/71516666-8549-4117-b0ca-bd8594eca1cf

<br>
<br>




