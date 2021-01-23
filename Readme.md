![Redstone Sidekick](https://i.imgur.com/v3yk2du.png)

Redstone Sidekick is a companion application for Minecraft that allows you to autogenerate crafting trees and gathering lists for your projects from Minecraft structure files or WorldEdit .schem files. You can track your progress as you gather and craft your creation, and you can share your material list with others through simple project codes that your friends/audience can copy and paste into Redstone Sidekick.

## Installation

Download Redstone Sidekick Here: 
[Release Page](https://github.com/NatickSoftware/RedstoneSidekick/releases/)

Open up RedstoneSidekick.exe and get crafting!


## Give Some Feedback

Twitter: [@RS_Sidekick](https://twitter.com/RS_Sidekick)

Submit a Bug Report or Feature Request: [Issues Page](https://github.com/NatickSoftware/RedstoneSidekick/issues)

Reddit Post: [Redstone Sidekick](https://www.reddit.com/r/Minecraft/comments/kyvbn9/redstone_sidekick_a_minecraft_crafting_tree_and/)

YouTube: [Redstone Sidekick Tutorial](https://www.youtube.com/watch?v=gCvlVOLV_6g)


## A Brief Guide to Redstone Sidekick

For a video tutorial and introduction, check out this YouTube video: 
[![RS Tutorial Video](https://img.youtube.com/vi/gCvlVOLV_6g/maxresdefault.jpg)](https://www.youtube.com/watch?v=gCvlVOLV_6g)

Below is a quick guide to the basic functionality of Redstone Sidekick. In this guide you'll see how to:
* Create a project from a Minecraft structure file
* Add/Remove Items
* View your project's gathering list 
* Save, load, and share projects through .rsp files or project codes.

## Creating a Project From a Minecraft Structure File or World Edit .schem file.
If you need help creating a structure file in Minecraft, there is a [tutorial here.](https://www.digminecraft.com/getting_started/structure_block_corner_mode.php "tutorial here.")

In brief, a structure file, (marked by the .nbt file type) is a file used by Minecraft to save a three dimensional section of blocks. Redstone Sidekick can read these files to give you a condensed crafting tree and gathering list for that structure. 

In order to create a RS Project from a structure file, go to the top menu in Redstone Sidekick, select "New From Structure" or "Add Structure" and select your .nbt file in the file explorer. You can load .schem files this same way.

![New From Structure](https://i.imgur.com/v564LRm.png)

Your structure will populate the crafting list in the main window, and look something like this:

![Carousel Project](https://i.imgur.com/mYgrw3V.png)

## Adding and Removing Items

Sometimes, you may have items in the structure file that you do not want to actually replicate in your crafting list, or you may want to add items to your list that were not present in the structure file. You can remove items by selecting them in the Crafting Tree tab, and pressing the "Remove Selected" button on the Crafting Tree menu.

To add items, use the categorized, searchable list of blocks on the right hand side of the project window. Open it by hitting the plus button on the right, and double click the item you want to add. It will add the item to the project with a quantity of one, and then you can edit the quantity by selecting it.

In the example project, we removed extra items from the structure like the grass blocks and scaffolding it was placed on, and added 10 diamonds from the item menu on the right.

![Adding and Removing items](https://i.imgur.com/3eWhvik.png)

## The Crafting Tree and The Gathering List

So far, we've looked at the project through the crafting tree view. The crafting tree view shows you every block that is in the final structure. For blocks that have crafting recipes to create them, there is a plus button on the left of the block display to see the component parts. As you add ingredients or mark them off as gathered, the crafting tree will update and sync with your gathered materials, to simplify your project over time.

![Expanded Crafting Item](https://i.imgur.com/42hBDcE.png)

The gathering list view lets you see what you will actually need to gather to create the structure. The gathering list aggregates all the material counts for each final block in the structure, and condenses them into a list of the base materials.

In the gathering list view, you can keep track of how many items you have gathered. When you have gathered enough, Redstone Sidekick will check that item off your list. If you go back to the Crafting Tree view and edit your structure, the program will remember your previous quantities, and adjust accordingly.

When you have enough of an item, you can click it's image to check it off, or the gathering list will check it off when you add a quantity that tells it you have enough of the item.

Both the crafting tree and the gathering list can be sorted in the top right corner to show items in particular orders.

![Gathering List Items](https://i.imgur.com/GOyHKWI.png)

## Saving and Loading Projects
Redstone Sidekick gives you two methods for saving projects: Redstone Sidekick Project files, and Project Codes. 

#### Redstone Sidekick Project Files (.rsp)
Project files save your project to your local machine, and store:
* The Project Name
* The Crafting Tree List
* Your Gathering List Progress

This is a complete save of your project, and will allow you to continue your gathering from where you left off. 

You can create/load these files by hitting the "Save Project" and "Load Project" buttons on the top menu.

However, because this saves your gathering progress and requires sharing a file, this isn't the ideal way to share projects with others. For that, there are Project Strings.

#### Project Codes
Project codes are designed for easy sharing of projects with other players. These are especially helpful for content creators, as a tutorial maker can include a project code in their YouTube description or Twitch chat, and easily share the item list for a project with their audience, with no download necessary.

Project codes do not include the gathering progress for the project. This means any time you load a project code it will create a "fresh" project for you. Because of this, you can easily share a project you're already working on with a friend or an audience, and they won't have to remove your progress to make their own copy.

In order to create a project code for your RS Project, go to the top menu and press, "Create Project Code".

To create a project from a project code, press "Load Project Code". You will be prompted to paste your project code into a pop up window, and it will populate a new project with that data.

![Input Project Code](https://i.imgur.com/3kf9yRf.png)


## Wrap Up

Those are the basics of Redstone Sidekick! For more details, check the YouTube video at the top of the Readme.

Thank you for taking a look at Redstone Sidekick. I hope it makes your time playing Minecraft even more enjoyable. If Redstone Sidekick is a help to you, please share it with your friends, and talk with me on Twitter, Reddit, or in the Github Issues or discussions tab on the project page. If it ends up being something that brings value to the Minecraft community, I have so many exciting ideas and features I would love to add to this project to make it even more helpful.

Thanks again and keep crafting!

- Nick (Dekori)


## License
Check out the License and Readme in the RedstoneSidekick download. All third party libraries are used within their licenses, and Mojang is the sole owner of Minecraft and all of its' assets.
