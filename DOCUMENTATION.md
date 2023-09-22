Unity Pun Multiplayer Framework V0.1
Max Premo
09/22/2023

**Requirements**

- Unity 2021.3 Or Higher
- Photon Pun 2 (Installed and Setup)
- Text Mesh Pro Package

**Networked Behaviours**

// Room Structure

Launcher.cs
/* Our Network Lobby Manager which handles callbacks, joining/leaving rooms, assigning custom properties. */

RoomManager.cs
/* Persistent room data throughout the game */
- Initilization in the lobby scene

// Player Structure

PlayerIdentity.cs
/* The base player identitiy within the room, This handles spawning/despawning the PlayerManager.cs. 
  As well as any other player data that needs to be stored persistently outside of the controller*/

PlayerManager.cs
/* The players visualization throughout the room. This script is intended to connect and handle all user inputs,
  controllers, and animators. */
