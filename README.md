# Aliina's Progamming Portfolio

Portfolio for college programming coursework completed by Aliina E.
<br/>
### Crafting System

A simple console application utilizing lists and arrays, if statments, foreach loops, and many other instances of foundational C# code. It allows a player to craft items from a given list of recipes, using ingredients stored in their inventory. It also includes a shop to buy and sell items from using currency.  

<img width="810" height="649" alt="image" src="https://github.com/user-attachments/assets/e2052484-764c-41fc-a146-7f5d0f79b16e" />  

The opening of the game. It instantiates a Player, accepting and storing a name before returning that name along with the player's currency. It then displays a menu, and instructions for navigating it. The inventory displays a list of items the player has, along with their quantity and value.


<img width="551" height="512" alt="image" src="https://github.com/user-attachments/assets/28952878-b5e3-4cb7-9ca1-0cd6416fd09b" />  

The game has a functional Craft method within the Person class. It may not be the most elegant, but it fulfills its intended purpose based on the content currently in the game. It performs a check to see if the player possesses sufficient amounts of the required ingredients, removes the ingredients from the player's inventory, and adds the crafted item in their place.


<img width="653" height="177" alt="image" src="https://github.com/user-attachments/assets/fe11cd6e-fd4f-48ed-982f-55a3829b07df" />  

A SearchInventory method was coded, but ultimately not implemented. Pieces of this code were, however, reused to make the Check method that would be necessary for the Craft method to work as intended.


<img width="818" height="520" alt="image" src="https://github.com/user-attachments/assets/b35ec628-e65f-44a0-b2e7-a7aafe0c1789" />  

The vendor NPC was given dialogue as a fun extra feature. This includes a means of changing the vendor's name, mostly as a joke, but also to demonstrate that their name is an attribute and not hard-coded into the displayed text.


### Creature Generator

A WPF application made to demonstrate inheritance and enums. It features several locations for the player to go to, each with a generated set of creatures with randomized names and stats. Each location has a unique creature type that derives from the general Creature class, with override methods drawing from the base class.

Images go here  
Captions go here

### Chicago Weather Reader

A console app that uses an API call to give the current weather in Chicago, Illinois. API key obtained from openweathermap.org.

Images go here  
Captions go here

### Boggie

A console app that replicates the word game Boggle, using an array to create the board and drawing from external files to determine accepted words. Tracks score and entered words on-screen during gameplay.

Images here  
Captions here

### Save System Demo

A WPF app that can save data to an external file. Includes an inventory that items can be added to, and files that store items to be added to the game on startup.

Images  
Captions

### Path in the Woods

A text-based adventure game made as a WPF application. It allows the player to take quests from randomly-generated NPCs in a village setting, then set out into the woods to overcome obstacles and complete objectives. Upon turning in completed quests, the player would earn points and reward money, allowing them to take on more difficult quests.

Images
Captions
