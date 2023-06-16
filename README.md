# Wokwi-Testing

![Wokwi Screenshot](https://firebasestorage.googleapis.com/v0/b/hanlon-blog.appspot.com/o/BlogImages%2FScreenshot%202023-06-15%20at%2010.47.08%20PM.png?alt=media)

### To run the simulator:

1. Clone the repository
   -    `git clone https://github.com/SFSU-Fog-City-Rocketry/Wokwi-Testing.git`
2. Open the folder in VSCode
3. Install the [Wokwi VSCode Plugin](https://marketplace.visualstudio.com/items?itemName=Wokwi.wokwi-vscode).
4. Open the command pallette (Ctrl+Shift+P on Windows, Cmd+Shift+P on Mac) and select "Wokwi: Open in Wokwi Simulator"
5. You will be prompted to get a license key. Click the link and follow the instructions. Wokwi is currently offering licenses for free.
   -    You will need to create an account with Wokwi to get a license key. I recommend connecting the GitHub account you used to clone the repository.
   -    You will be asked to confirm twice, once in your browser and once in VSCode. Click "Allow" both times.
6. If the simulation doesn't open after the license is applied, execute the "Wokwi: Open in Wokwi Simulator" command again.

### Files in this repository:

-    `README.md`: This file.
-    `LICENSE`: The license for this repository (MIT License).
-    `.gitignore`: Tells git to ignore certain files, like for example the `DS_Store` file that Macs create.
-    `esp-at.bin`/`esp-at.elf`: The firmware for the ESP32.
-    `wokwi.toml`: Configuration file for Wokwi.
-    `diagram.json`: This file defines what appears on the diagram in the simulator. I'd recommend going [to the Wokwi site](https://wokwi.com) and using the GUI to create a diagram, then copying it back into this file to make changes.
