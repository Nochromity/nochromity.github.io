# Aliina's Progamming Portfolio

Portfolio for college programming coursework completed by Aliina E.
<br/>
### Crafting System

A simple console application utilizing lists and arrays, if statments, foreach loops, and many other instances of foundational C# code. It allows a player to craft items from a given list of recipes, using ingredients stored in their inventory. It also includes a shop to buy and sell items from using currency.  
<br/>

<img width="810" height="649" alt="image" src="https://github.com/user-attachments/assets/e2052484-764c-41fc-a146-7f5d0f79b16e" />  

The opening of the game. It instantiates a Player, accepting and storing a name before returning that name along with the player's currency. It then displays a menu, and instructions for navigating it. The inventory displays a list of items the player has, along with their quantity and value.
<br/><br/>

<img width="551" height="512" alt="image" src="https://github.com/user-attachments/assets/28952878-b5e3-4cb7-9ca1-0cd6416fd09b" />  

The game has a functional Craft method within the Person class. It may not be the most elegant, but it fulfills its intended purpose based on the content currently in the game. It performs a check to see if the player possesses sufficient amounts of the required ingredients, removes the ingredients from the player's inventory, and adds the crafted item in their place.
<br/><br/>

<img width="653" height="177" alt="image" src="https://github.com/user-attachments/assets/fe11cd6e-fd4f-48ed-982f-55a3829b07df" />  

A SearchInventory method was coded, but ultimately not implemented. Pieces of this code were, however, reused to make the Check method that would be necessary for the Craft method to work as intended.
<br/><br/>

<img width="818" height="520" alt="image" src="https://github.com/user-attachments/assets/b35ec628-e65f-44a0-b2e7-a7aafe0c1789" />  

The vendor NPC was given dialogue as a fun extra feature. This includes a means of changing the vendor's name, mostly as a joke, but also to demonstrate that their name is an attribute and not hard-coded into the displayed text.
<br/><br/>

### CritterPasture

A WPF application made to demonstrate inheritance and enums. It features several locations for the player to go to, each with a generated set of creatures with randomized names and stats. Each location has a unique creature type that derives from the general Creature class, with override methods drawing from the base class.  
<br/>

<img width="782" height="511" alt="image" src="https://github.com/user-attachments/assets/1ce49f4f-2d15-4f22-b877-b3f0dce7231e" />  

The program has a button that opens a menu for moving between locations, where each generated set of creatures can be viewed. Each set is generated on startup and remains consistent upon leaving and re-entering a location. For new sets, the player would have to close and reopen the program.
<br/><br/>

<img width="815" height="454" alt="image" src="https://github.com/user-attachments/assets/1195787e-b241-479f-90a7-4bf7eb4247a6" />  

This is the code that sets up the text that is displayed. It displays information about each Creature in each Location, along with the text for how they eat and communicate. Unique Creatures, instances of child classes of the Creature class, have extra activities they can perform. As can be seen from the comments in this section, I struggled with implementing this extra activity because it would not recognize a Wyrmling as a Creature the way I thought it would. I was able to resolve the issue with assistance from my professor.
<br/><br/>

<img width="442" height="522" alt="image" src="https://github.com/user-attachments/assets/e67dbcdc-17a5-4af2-8e76-b32e00311925" />  

This is how the Move menu works for changing location. Showing the menu and hiding the menu are both implemented twice, with one method activating through pressing the "Go Somewhere" and "Cancel" buttons, while the other has no parameters and exists so that other methods can call it. For instance, moving to a different location closes the menu automatically.
<br/><br>

<img width="404" height="272" alt="image" src="https://github.com/user-attachments/assets/d038ea53-429e-4c88-b7aa-a6a94cc7e68f" />  

This code shows one of the child classes of the Creature class. The Creature class has Eat and Communicate methods, and the Wyrmling class has override methods for each of these. The overridden Communicate method ended up being unnecessary, as the base method was altered to include a creature's noise, should they have one, by default.
<br/><br/>

### Chicago Weather Reader

A console app that uses an API call to give the current weather in Chicago, Illinois. API key obtained from openweathermap.org.  
<br/>

<img width="320" height="121" alt="image" src="https://github.com/user-attachments/assets/efe91823-e13b-4a1c-867e-cac3345eff7d" />  

The program is very simple, calling a weather API and displaying the information it provides. There is no interactivity beyond opening the program.
<br/><br/>

<img width="765" height="332" alt="image" src="https://github.com/user-attachments/assets/be2ee0dd-0c2f-40c6-8eba-20f6cda23047" />  
  
This is all of the code for the program, with the API key obscured. This code was demonstrated in class as part of a demonstration, and so credit for it goes to Professor Janell Baxter. The work I contributed was to acquire and insert the API key.
<br/><br/>

### Boggie

A console app that replicates the word game Boggle, using an array to create the board and drawing from external files to determine accepted words. Tracks score and entered words on-screen during gameplay.  
<br/>

<img width="638" height="444" alt="image" src="https://github.com/user-attachments/assets/bd235568-4eca-4d9e-b71e-14ea66ecb2b4" />  

The game allows the player to enter a word, and if the word is correct, it is recorded on-screen for the player to keep track of what they've entered, along with their score. The program clears lines so that the console is kept uncluttered and things stay in the same position for every action the user performs.
<br/><br/>

<img width="763" height="245" alt="image" src="https://github.com/user-attachments/assets/0ef5a5a2-baa7-4920-960b-27372a8636bd" />  

I had some difficulty getting the array to display correctly, but I had a number of guides I could follow to figure it out, including my own old coding assignments from Programming I. The board's letters are hard-coded in, but could easily be outsourced to an external file with multiple different string arrays for the program to randomly choose from.
<br/><br/>

<img width="415" height="516" alt="image" src="https://github.com/user-attachments/assets/3ed3ed6c-dc3d-4e57-8497-a57b57b678d6" />  

I'm fairly proud of the code that went into making the game work the way it does, particularly the formatting for displaying found words. I realize now that there is no means for the program to prevent repeat correct answers from being entered multiple times, but there is always room for improvement.
<br/><br/>

<img width="512" height="367" alt="image" src="https://github.com/user-attachments/assets/746f4988-53d3-424d-934f-470f978d77f4" />  

RunGame and PlayGame keep the game running continuously as long as gameActive is true. A timer class was made, but the feature was not implemented fully. If the game had a functional timer, gameActive would change to false when it reached 0. As it currently stands, there is a debug feature that manually changes gameActive to false so as to test the EndGame method.
<br/><br/>

### Save System Demo

A WPF app that can save data to an external file. Includes an inventory that items can be added to, and files that store items to be added to the game on startup.

Images  
Captions

### Path in the Woods

A text-based adventure game made as a WPF application. It allows the player to take quests from randomly-generated NPCs in a village setting, then set out into the woods to overcome obstacles and complete objectives. Upon turning in completed quests, the player would earn points and reward money, allowing them to take on more difficult quests.

Images
Captions
