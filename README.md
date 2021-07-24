# Item-Smelder
TF2 is my favourite online FPS game. There are 9 playable classes in the game, each with their own weapons. Players are randomly given weapons in the game, each weapon having it's own perks and drawbacks. Some weapons can be used by multiple classes. 2 weapons used by the same class can be combined to make scrap metal, which in turn can be used to create more weapons or sold on the market. I created this project to find the optimal smelding process to create the maximum number of scrap metal. 

<img src="/img/example.png" height=500> <img src="/img/example2.PNG" height=500> <img src="/img/output.PNG" height=500>

Above are examples of the output. On the left is a visual example, and on the right is text-based. These are interpreted as instructions, which weapons to combine to produce scrap. 

## Note
It is important to note that the program does consider items that aren't usable in crafting. For example, if there are 3 copies of an item, but only 2 of them are usable in crafting, during the smelding process, it may appear that you're using up all of the copies (because the non-craftable copy will not be shown in the smelder options!). However, you can verify that you do indeed have 3 copies by checking the backpack, and thus can safely proceed with smelting. 
