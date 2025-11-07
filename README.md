The repository is divided in 2 folders:
1. Folder containing the developement environment for Eclipse IDE.
2. Export folder containing the runnable file and game.

To compile the tool open the first folder with Eclipse IDE. Right click on the project and select export -> Runnable Jar File. Then make sure the option to copy the required libraries is selected. For this to work make sure you have the Ludii-x.xx.jar file as a referenced library.

To run the tool, make sure to have the command line open in the second folder and simply run `java -jar game_eval_tool.jar --fileAppendNum 1 --modification "some description"`, for example. Additionally, make sure there is a file named `Neutron.lud` since the tool looks for a game with this name (can be added as a argument if required).
The other arguments are displayed by using `java -jar game_eval_tool.jar --help`.
