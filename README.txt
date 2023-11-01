
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





GRADLEW TASKS:
   > Task :tasks

   ------------------------------------------------------------
   Tasks runnable from root project 'Midas'
   ------------------------------------------------------------

   Build tasks
   -----------
   assemble - Assembles the outputs of this project.
   build - Assembles and tests this project.
   buildDependents - Assembles and tests this project and all projects that depend on it.
   buildNeeded - Assembles and tests this project and all projects it depends on.
   classes - Assembles main classes.
   clean - Deletes the build directory.
   jar - Assembles a jar archive containing the main classes.
   testClasses - Assembles test classes.

   Build Setup tasks
   -----------------
   init - Initializes a new Gradle build.
   wrapper - Generates Gradle wrapper files.

   Documentation tasks
   -------------------
   javadoc - Generates Javadoc API documentation for the main source code.

   ForgeGradle runs tasks
   ----------------------
   genEclipseRuns
   genIntellijRuns
   genVSCodeRuns
   prepareRunClient
   prepareRunData
   prepareRunGameTestServer
   prepareRuns
   prepareRunServer
   runClient
   runData
   runGameTestServer
   runServer

   Help tasks
   ----------
   buildEnvironment - Displays all buildscript dependencies declared in root project 'Midas'.
   dependencies - Displays all dependencies declared in root project 'Midas'.
   dependencyInsight - Displays the insight into a specific dependency in root project 'Midas'.
   help - Displays a help message.
   javaToolchains - Displays the detected java toolchains.
   outgoingVariants - Displays the outgoing variants of root project 'Midas'.
   projects - Displays the sub-projects of root project 'Midas'.
   properties - Displays the properties of root project 'Midas'.
   resolvableConfigurations - Displays the configurations that can be resolved in root project 'Midas'.
   tasks - Displays the tasks runnable from root project 'Midas'.

   IDE tasks
   ---------
   cleanEclipse - Cleans all Eclipse files.
   eclipse - Generates all Eclipse files.

   Jarjar tasks
   ------------
   jarJar - Create a combined JAR of project and selected dependencies

   Publishing tasks
   ----------------
   generateMetadataFileForMavenJavaPublication - Generates the Gradle metadata file for publication 'mavenJava'.
   generatePomFileForMavenJavaPublication - Generates the Maven POM file for publication 'mavenJava'.
   publish - Publishes all publications produced by this project.
   publishAllPublicationsToMavenRepository - Publishes all Maven publications produced by this project to the maven repository.
   publishMavenJavaPublicationToMavenLocal - Publishes Maven publication 'mavenJava' to the local Maven repository.
   publishMavenJavaPublicationToMavenRepository - Publishes Maven publication 'mavenJava' to Maven repository 'maven'.
   publishToMavenLocal - Publishes all Maven publications produced by this project to the local Maven cache.

   Verification tasks
   ------------------
   check - Runs all checks.
   test - Runs the test suite.

   Rules
   -----
   Pattern: clean<TaskName>: Cleans the output files of a task.
   Pattern: build<ConfigurationName>: Assembles the artifacts of a configuration.

   To see all tasks and more detail, run gradlew tasks --all

   To see more detail about a task, run gradlew help --task <task>

   Deprecated Gradle features were used in this build, making it incompatible with Gradle 8.0.

   You can use '--warning-mode all' to show the individual deprecation warnings and determine if they come from your own scripts or plugins.

   See https://docs.gradle.org/7.5.1/userguide/command_line_interface.html#sec:command_line_warnings

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
