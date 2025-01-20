# Setup Guide
https://ryujinx-emulator.com/setup/windows

Requirements

In order to use Ryujinx your computer will need:

    At least 8GB RAM
    A video card/GPU that supports OpenGL 4.5/Vulkan 1.2 or higher. Make sure the drivers are up-to-date.
    Your prod.keys and either your dumped firmware or game cartridge untrimmed XCI
    Your dumped Nintendo Switch games or homebrew
    Windows 10 RS4 (Redstone 4, version 1803) or newer is required.

A recommended baseline system (native resolution and framerate) would look something like:

    CPU: Ryzen 5 3600
    RAM: 16GB DDR4
    GPU: NVIDIA GTX 1060 6GB

Placement of prod.keys
By default Ryujinx will use %appdata%/Ryujinx to store all of it’s permanent files. This includes firmware, save files, shader caches and other configuration. If you wish Ryujinx to be fully self-contained you may use portable mode!
 

    Now that you’ve downloaded Ryujinx, open it and extract the contents of the publish folder onto your drive in the location of your choice. We recommend against using your desktop or the root of any drive as these can sometimes be protected.
    Navigate to where you extracted the Ryujinx files, and double-click on Ryujinx.exe. This will launch the emulator and you will be met with the following message (don’t worry; this is normal!)

    Click OK on the warning box.
    Now that Ryujinx has been launched, the proper folders have been created for you in your %appdata% folder.
    Click File at the top left of the Ryujinx window, and then click Open Ryujinx Folder.

    Navigate down into the system subfolder and paste your prod.keys file here. The file/folder structure should look like this (RyujinxEmulator substituted for your username):

    Close and reopen Ryujinx so that the prod.keys file is validated.
    You’re done installing keys!

Installation of Firmware
Now that your keys are installed, it’s time to install a firmware. Make sure you have an untrimmed XCI file of a recent game cartridge you dumped, or have compiled your dumped firmware into a ZIP file.

    Open Ryujinx. There should be no warning about KEYS.md anymore; if you still get the warning, go back through the prod.keys steps and ensure you have placed the file correctly.
    Now that Ryujinx is open, click Tools > Firmware > Install from XCI/ZIP

 This brings up the “Choose the firmware file to open” window.

Using the Ryujinx window, navigate to the location of your dumped XCI file and click Open. You will be asked to confirm whether you want to install the firmware. Make sure your prod.keys are at least as new as the firmware you are installing!

(Your firmware version number may vary)

    Click Yes. You will see a message that the firmware is installing and was successfully installed:

Click OK. If all went well, you will now see your firmware version listed as the “System Version” in the bottom right hand corner of the main Ryujinx window.
What's Next?

Now that you’ve successfully configured Ryujinx on your Windows PC, you should learn the basics on how to use the switch emulator. To know more about how to add games, set up controls, enhance graphics and more – access our dedicated knowledge base for more info.

For any issues regarding Ryujinx, visit our troubleshooting section.
