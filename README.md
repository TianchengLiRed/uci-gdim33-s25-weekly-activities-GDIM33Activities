# GDIM 33 In-Class Activities
## W1
### Activity 1
[Inspo Board](https://www.figma.com/board/1lVY0uE62CHtYDsnHanPPt/Untitled?node-id=0-1&t=5wOlKwMCmGqjQ2Ic-1)

1. I'm actually have a exact pattern of my game, i really like games that you don't control a character like paper please or dont feed the monkey. no matter how i brainstorm i always remain key tactical game mechanics. And I'm looking for connections to help me figure out how my game can tell an good story, Im focus on how gameplay contribute for plots and stories. Also I consistently interested in supernatural element. I dont have a specific art style preference but i think i will convey a horror style through simple art, just like whos lila, black and white pixel realism style.

2. one of my table mates want to create a  2D platform game that takes place in the isolated horror island, we have similar styles that both of us love how horror element to stimulating players' senses in the game, create a horror atmosphere through the environment. And we are both interested in horror exploration genre like resident evil and backrooms which inspired us with horror theme.

3. one of the LA really like multiplayer FPS cooperation game, multiplayer pve game like Deep Rock and GFTO. We have similar taste that both of us are interested in shooter game, which inspired me to create a tactical game, even though is about ghost hunting but it is more similar with tactical shooter game, I add mnay modern weapon like guns as the players primary attack method. Also we both interested in cooperation content and PVE, I think that tactical games can maximize the potential for cooperation just like Divinity or Baldur's gate, It is another form of cooperation.

### Activity 2


![03d61bea0e499eb1a3aaca882985cbe2](https://github.com/user-attachments/assets/a34636a4-791b-4f8b-87f9-a62ee900f9af)



## W3
### Activity 1

<img width="1706" height="1279" alt="cc10b0104e48929806ff29542ee490ee" src="https://github.com/user-attachments/assets/0b7314e7-0668-4dc5-afc9-3a058d02c963" />

### Activity 2

1. I think store event name in to a scene variable is advantageous because I can get the clickWalrus through Get Variable node, instead of directly type the event name in to the node, even though you want to change the event name, you dont have to change every name in the visual scripting but just change the value in clickNpcEventName. Also stored it in to the Scene Variable enables you to invoke the same event across graphs in different GameObjects, people dont have to set target in the event node, it makes visual scripting easier.

2. using debug.log() in the visual scripting can help me determine the exact location of bugs. For example,I added 2 debug.log in the function of click the walrus and state transition. When i testing my game i finds out that only debug.log  in the click function has been called but mnot the state transtition, so that i can locate the bug that is on the state transition and fix the bug that emerges because of the wrong event name and custom event on the transition has not been called. Its hard for visual scripting to navigate bugs through console, using Debug.log can help us locate the bug through a process of elimination.

3. Set cursor is actually not relvant with my Vertical Slice. Because my game is a 3D Top-Down horror game. The game's camera angle actually remains constant,only move follow the players location. The game's camera perspective does not change in response to mouse movement. And most interactions are performed through mouse clicks.

4. The concept of game state are highly relvant with my Vertical Slice. I can use it to organize different states of the ghost, change their appearance and behavior based on different conditions, keep mutually exclusive and avoid conflict between differnt states. For exmaple the ghost has different states based on players location, if player in the ghost detect range, ghost should change their random movement behavior of idle state to chasing, etc. I can use game state to achieve those kind of transition between states, different appearances and behaviors.

## W4
### Activity 1
playable: 

The basic movement, dialogue with NPC (branching choice) and interact with certain interactive objects outside of the station(first scene), 

The warchess movement base on grid and pathfinding by click the location of the map, shooting and aiming base on postition of the mouse.

MainMenu Ui base interaction.


playtest goal: 
1. testing the feature of pathfinding for different move range.
  
2. testing the aim in shoot feature to see if am function is accurate.
  
3. the automatic turn update is enough for people to think and act.
   
4. testing if isometric is suitable for mechanics( point to move and aim function)

Members: Han Yang, Leo Abe, Jing Cheng, Tiancheng Li.

Notes:
NO frog models.
basic code is cool, gameplay is nnot enough, not too much feeback for player, they dont understand what is going on
people dont understand what to do because there is not hint for player what button they can click or what action they can perform.
need more art assets, the aim system is werid, it doesnt really following the mouse(bug).

### Activity 2

1. writer could add more dialogue without add any code，you only need to add more line and reply option in the scriptableobjects that you created, because the whole dialogue system is based on scriptableobject in your current line, instantiate buttons base on numbers of your reply option in your current line and move to next line base on your other scriptableobject in SO in current line corresponding to the replyOption. When dialogue move to the new line, it will trigger this event and repeat this step. So your dialogue system will be change every time you move in to a new dialogue line based  on your new SO in new dialogue line So you just need to add more information in your scriptableobject the dialogue system will show your dialogue based on dialogue scriptableobject.

2. There's no actual limit of the number of the dialogue node you code create, but based on the computer performance， the more dialogue node in the game, will consume more computer resources, so in order to make sure the game run smoothly, that might be one of the limit of  the number of the dialogue.

3. Regenerate Node is how unity go through every C# code that i create in the project and update new nodes corresponding codes that i created, so you can  use it in the Graph.

screenshot for bonus credit, sprite on the image will change base on assigned sprite in the corresponding 
<img width="764" height="435" alt="截屏2026-04-22 19 31 03" src="https://github.com/user-attachments/assets/4cd8bdb8-b74b-4f85-af69-dfedca074d20" />
<img width="595" height="449" alt="截屏2026-04-22 19 31 13" src="https://github.com/user-attachments/assets/d1561d50-cb08-45d4-a02d-a3496fa0fd49" />
<img width="459" height="291" alt="截屏2026-04-22 19 31 35" src="https://github.com/user-attachments/assets/32cd1140-5d0e-4815-9205-fcde4ad0c920" />
<img width="488" height="306" alt="截屏2026-04-22 19 31 45" src="https://github.com/user-attachments/assets/f2ba1fec-f71f-4986-afaf-ea7a56a7b5d0" />
<img width="444" height="283" alt="截屏2026-04-22 19 31 48" src="https://github.com/user-attachments/assets/403a892a-5e0c-4203-ba23-8d6fdcf4ef10" />
dialogue node
<img width="899" height="422" alt="截屏2026-04-22 19 29 06" src="https://github.com/user-attachments/assets/c913ba86-13a5-49b6-859d-3a4943d74aaa" />
<img width="603" height="502" alt="截屏2026-04-22 19 29 48" src="https://github.com/user-attachments/assets/ff114f12-d74e-4ec1-a9ae-08507c67a76b" />
<img width="896" height="520" alt="截屏2026-04-22 19 50 02" src="https://github.com/user-attachments/assets/2838bf80-03ac-49c3-aaf2-6d8369ea29c7" />
