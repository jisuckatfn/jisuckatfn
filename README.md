- 👋 Hi, I’m @jisuckatfn
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
jisuckatfn/jisuckatfn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Flags from decompiled scripts: 0 = normal exit and closes door. 1 = normal exit and closes door. 16 = teleports outside, door kept closed. (This flag does not seem to work for the front seats in buses, NPCs continue to exit normally) 64 = normal exit and closes door, maybe a bit slower animation than 0. 256 = normal exit but does not close the door. 4160 = ped is throwing himself out, even when the vehicle is still. 262144 = ped moves to passenger seat first, then exits normally Others to be tried out: 320, 512, 131072.
p4/p5: Unusued in TU27
This is the server-side RPC native equivalent of the client native SET_PED_INTO_VEHICLE.

Example: TASK::TASK_DRIVE_BY(l_467[1/22/], PLAYER::PLAYER_PED_ID(), 0, 0.0, 0.0, 2.0, 300.0, 100, 0, ${firing_pattern_burst_fire_driveby}); Needs working example. Doesn't seem to do anything. I marked p2 as targetVehicle as all these shooting related tasks seem to have that in common. I marked p6 as distanceToShoot as if you think of GTA's Logic with the native SET_VEHICLE_SHOOT natives, it won't shoot till it gets within a certain distance of the target. I marked p7 as pedAccuracy as it seems it's mostly 100 (Completely Accurate), 75, 90, etc. Although this could be the ammo count within the gun, but I highly doubt it. I will change this comment once I find out if it's ammo count or not.

This is the server-side RPC native equivalent of the client native TASK_DRIVE_BY.
Ragdoll Types
0: CTaskNMRelax 1: CTaskNMScriptControl: Hardcoded not to work in networked environments. Else: CTaskNMBalance

This is the server-side RPC native equivalent of the client native SET_PED_TO_RAGDOLL.


This is the server-side RPC native equivalent of the client native TASK_LEAVE_VEHICLE.

