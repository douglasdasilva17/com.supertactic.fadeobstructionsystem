# Fade Obstruction System

The `Fade Obstruction System` is a Unity asset that automatically applies a fade effect to objects obstructing the view between the camera and the player (or any defined target). This improves scene readability in 3D games, ensuring walls, trees, or other elements don’t block the player’s visibility.

---

## Features

- Detects objects blocking the line of sight from the camera to the target.
- Applies smooth fade (alpha-based or custom shader).
- Quick and simple setup.
- Supports multiple targets (player, NPCs, etc.).
- Fully customizable: intensity, duration, materials, and layers.

---

## Installation

1.  Go to **Window > Package Manager**.

2.  Click the **+** button → **Add package from git URL...**.

3.  Paste the repo URL: https://github.com/douglasdasilva17/com.supertactic.fadeobstructionsystem.git


## How to use

1.  Create a **Layer Mask** for the **obstacle** object. 

2.  Attach the script `FadingObject` to your **obstacle** object.

3.  Attach the script `FadeObjectBlockingObject` to your Player.

4.  Done!