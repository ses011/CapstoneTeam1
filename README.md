# CapstoneTeam1

#### If when going to launch the unreal project you're getting a "SERIALCOM needs manually rebuilt" error, or something along those lines, do the following
* Make sure Visual Studio is up to date and has C++ installed
* Delete everything in the Plugins folder, then redownload the 5.3 plugin from [here](https://github.com/videofeedback/Unreal_Engine_SerialCOM_Plugin)

#### If you get the git issue where the screen is blue, do esc, then :q

#### How to download the maze generator 
https://www.youtube.com/watch?v=jtrW2ZxIhQ4
that video will walk you through the steps. If you dont want to watch the whole video just follow these steps here
* In the Epic Games FabLab download "Maze Generator" by Lowkey Store.
* Go to Edit tab --> Plugins at the bottom of the tab
* In Plugins search Maze Generator, cluck the check box, then restart now
* In the content browser go to Engine --> Plugins --> Maze Generator Content
* Create a child blueprint class of BP_Maze
* Double click the child BP
* Choose Kruskal's 
