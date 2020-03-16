Project progress report
Changqi Chen , Michael Douglass, Mark Liu
March 16, 2020
Abstract
Our project for the class is based around the Malmo platform for Minecraft. We want an AI agent to perform steps within Minecraft that a normal human player would perform. That includes mining wood, creating crafting tables, creating types of pickaxes (wood, stone, iron), and finding materials to craft with (stone, iron, diamonds). The AI has to perform these tasks in specific orders (E.G mining wood, creating crafting tables, creating wood pickaxe). Also each major milestone of creating a pickaxe has subtasks of finding the materials to create the pickaxe with. 

So far what we have been able to accomplish is the beginning task needed for the rest of the tasks. Our AI is able to find and mine wooden logs, the basis of creating pickaxes and crafting tables. It also is able to avoid lava spots so as to not continually die over and over from falling into it. The AI also avoids hitting dirt blocks over time and only hitting the wooden logs due to the reward system laid out for the AI.

Introduction
Our project is about the Malmo Platform for Minecraft. We intend to create an AI that can do various tasks within minecraft that a normal player might do during their time playing the game. This includes mining wooden blocks, stone, iron ore, and diamonds. This also includes creating items in the game like crafting tables, sticks and pickaxes of various materials like wood and stone. The AI uses the wood blocks to create new items like the crafting table, sticks, and wooden pickaxe. The AI would use the wooden pickaxe to ultimately obtain a stone pickaxe. Then the AI would then use the stone pickaxe to obtain an iron pickaxe which then could obtain a diamond. 

We have a couple of problems that we are addressing. The first is how the environment around our AI should be created to maximize the learning that takes place. The second is stopping our agent from endlessly digging downwards and basically leaving the area of the environment. To combat these we created a specific environment with wooden logs sparsely put around it, with lava surrounding and below it so that our agent will learn to not go out of the environment. The problem was interesting for us in that, had we not found any way to change the environment for our AI to better suit our needs we would have had a very hard time completing our tasks in any sort of timely fashion. By creating the exact environment we need, we are able to test our AI and have the AI learn. Below is a picture of our environment.


