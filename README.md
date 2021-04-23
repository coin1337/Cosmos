# Cosmos
Cosmos is a open-sourced anticheat for Minecraft servers running Skript.


• Detections:
[Movement]
FlightY
Jesus
FlightFloat
Flight (NoMotion)
Flight (Hover)
Flight (+Y)
Flight (OnGround)
Bhop (Recurring Motion, Weird -Y Motion, OnGround Speed, OffGround Speed, Weird +Y Motion, Weird Y, Invalid Server Y, LowHop, Extra +Y, Constant Y)
Nofall (Invalid Packets)
Nofall2 (Movement)
Nofall3 (NoGround)
Self Damage (Movement)
Invalid Rotations
Vanilla Flight Packet
InvalidInventory (InvalidInv)
InventoryMove
InventorySimulate (Inventory Achievement Packet)
NoSlowDown

[Combat]
Killaura (in development)
Reach (With HitBox factorization)
CPS
CPS (Recurring CPS)
FastBow
AutoBlock
AutoBlock (Release Spam)
NoRotations
SelfHurt
MultiAura
NoSwing
Criticals
Criticals (Time between crit/packet)
Aimbot

[Exploit]
Timer(Packet Choking, Blink)
PingSpoof
Invalid Packets
Weird Packets
Crasher Check
Extra Packets

[Other]
FastEat
Build Reach
FastPlace




• Tested Server Software:
• Spigot
• PaperSpigot
• TacoSpigot
• Paper


• Permissions (Default Permissions)
- Cosmos.Anticheat (Cosmos command permission).
- Cosmos.Notify (Neon Notifications, you need this to get notifications).
- Cosmos.Kick.Bypass (Bypass Kicks/Bans from Cosmos).

• Commands:
/Cosmos (n aliases)
/Cosmos Alerts (on/off) # Enables alerts for your account.
/Cosmos Version # Gets Cosmos's current version, and checks for updates.
/Cosmos Player Violations (Player) # Gets the player's total violation count.
/Cosmos Player Stats (Player) # Checks Player's Ping / TPS / and banned status
/Cosmos Player Unban (Player) # Unbans a player from Cosmos.
/Cosmos Player Clear (Player) # Clears the player's current Violation.


• Dependencies:
• Skript 2.2-dev37c
• SkQuery 3.6.2-Lime
• Skellett 1.9.6b

