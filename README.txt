
Source installation information for modders
-------------------------------------------
This code follows the Minecraft Forge installation methodology. It will apply
some small patches to the vanilla MCP source code, giving you and it access 
to some of the data and functions you need to build a successful mod.

Note also that the patches are built against "un-renamed" MCP source code (aka
SRG Names) - this means that you will not be able to read them directly against
normal code.

Setup Process:
==============================

Step 1:
   Verify JDK 17 install with 'java -version' in-terminal.
   Verify that VS Code is installed. Launch it.

Step 2:
   Install all of the following extensions for VS Code:
      Gradle for Java
      Minecraft Essentials Extension Pack
      Extension Pack For Java

   If you installed extensions, restart VS Code.
   Verify that VS Code is running.

Step 3:
   In the project's root directory, verify that there is a directory listed as '.vscode'.
   In the top right, open a new terminal (or use the short cut ' ctr + shift + ` ').
   Run the following command: './gradlew genVSCodeRuns'

Step 4:
   Verify everything runs by using the 'runClient' option in the 'Run and Debug' section of VS.

Mapping Names:
=============================
By default, the MDK is configured to use the official mapping names from Mojang for methods and fields 
in the Minecraft codebase. These names are covered by a specific license. All modders should be aware of this
license, if you do not agree with it you can change your mapping names to other crowdsourced names in your 
build.gradle. For the latest license text, refer to the mapping file itself, or the reference copy here:
https://github.com/MinecraftForge/MCPConfig/blob/master/Mojang.md

Additional Resources: 
=========================
Community Documentation: https://mcforge.readthedocs.io/en/latest/gettingstarted/  
LexManos' Install Video: https://www.youtube.com/watch?v=8VEdtQLuLO0  
Forge Forum: https://forums.minecraftforge.net/  
Forge Discord: https://discord.gg/UvedJ9m  
