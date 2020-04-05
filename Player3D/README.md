# Intro

This package is a recreation of an older standart Unity asset, thats depricated in the newer unity3D versions. This Player package and
scripts are really basic, so there will be no trouble for you to understand how it works and how to config it, but just in case:

# Short descriptions about the elements in the package

`Player3D/` - Root folder for `Player_prefabs` and `Player_scripts` folders.

`Player_prefabs/` - Folder for the main `Player` prefab. This is the element you place in your Scene.

`Player_scripts/` - Folder for `CameraMove` and `PlayerMove` scripts, that will be covered below.

`PlayerMove.cs` - This script is responsible for `Player` prefabs movement. In it, you will find variables `Speed`, which controls
the main speed of the `Player`, and `SprintSpeedMultiplier`, which is used as a speed boost when `shift` is held with the `w` button.

`CameraMove.cs` - This script is responsible for the camera movement relative to your mouses movement. There are variable `speedH` & `yaw`, which
are used for camera X axis controlls, and `speedW` & `pitch`, which are used for camera Y axis controlls. Also, there is some camera
angle logic in it to fix the `Player` prefabs back from turning 180 on Y like somekind of lizard person.

# Controlls

For gamers, its the classic `ASWD (Movement)` + `Space (Jump)` + `Shift (Sprint)` and `mouse for camera movement`.

For non-gamer smurfs, `A (move to left)`, `D (move to right)`, `W (move to front)`, `S (move to back)`, `Shift (For sprint action, only works when W is held)`,
`Space (Jumping`) and `mouse for camera movement` (move mouse to left, camera moves to the left side, move mouse to the right, camera moves to the 
right etc.)
