# ProcessingMinecraft
A small Minecraft clone made in Processing.

## Setup Instructions

1. **Install Processing**  
   Download and install Processing from [processing.org](https://processing.org/download).

2. **Download Assets**  
   Download all files, including `ProcessingMinecraft.pde` and the `data` folder.

3. **Open the Sketch**  
   - Double-click `ProcessingMinecraft.pde` to open it in Processing.
   - Press **Command+S** (or **Ctrl+S** on Windows) to save the sketch, which will create a folder named `ProcessingMinecraft`.

4. **Move the Data Folder**  
   - Move the `data` folder into the `ProcessingMinecraft` folder that was just created.

5. **Install Required Libraries**  
   - In the Processing IDE, go to **Sketch -> Import Library -> Add Library...**.
   - Search for `Sound` by *The Processing Foundation* and install it.

6. **Run the Program**  
   - Run the sketch in Processing. If prompted for microphone access (due to the `Sound` library), click **Decline**.  
   - On macOS, the program will prompt you to open **System Settings**.  
     - Allow **Accessibility permissions** for Processing in **System Settings -> Security & Privacy -> Accessibility**.  
   - On Windows, run Processing as Administrator to allow mouse control via `Robot`.

---

## Controls

- **`esc` or `Command+W`**: Stop the code (locks your mouse, so this is the only way to exit).  
- **`WASD`**: Move.  
- **`Space`**: Jump.  
- **`Control` while moving**: Sprint.  
- **`Shift + Double Tap Space`**: Toggle creative mode.  
- **Numbers `1–8`**: Switch blocks.  
- **`V`**: Change perspective (first-person/third-person).  
- **`,` and `.`**: Adjust field of view (FOV).  
- **Arrow Keys**:
  - **Up/Down**: Change volume.
  - **Left/Right**: Change render distance.
