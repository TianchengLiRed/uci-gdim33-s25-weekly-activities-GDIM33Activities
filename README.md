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

## W5

### Activity 1

This system will allow player interact with specific objects and put a object to block the ghost's path, influence its movement towards player by editing navmesh.

Basic steps: 

1.  the basic object range detection and intercation
2.  create a specific object control
3.  make the block able to influence the current navmesh map and change ghost's path navigation.

Detailed steps:

1. Create a empty that stores Navmeshsurface, set the specific layer choice to generate navmesh and bake the Navmesh map. Add Modifier to some objects on the map. Run the game to check the Navmesh generated as the expected.
2. Create object with "Interactive" Tag, add dectection method to the Update in the AgentController to check every collider in the player's range if theres any interactive object with Interactive Tag.
3. Create a interaction method in the AgentController, Add a new interact state to current enum.Every time player press E change the states to the interact states. mouse select the specific object you want to interact with by using Raycast and activate and put on the ground , run the game to test the detection and interaction method works well.
4. Add a NavmeshObstacle component in the interactive objects, and unable it. create a interactive script to control the enable of the NavmeshhObstacle component every time player interact with them. (set specific animation if i want) run the game and stop after NavmeshObstacle is enable to check the current navmesh map.
5. integrate this feature to the turn system, everytime player choose to use this action by calling PlayerFinishedAction() at the end to update to new turn, to make sure only one action each turn. run the game to see if the turn is changed after action.

### Activity 2

Description of Accomplishment: Add a new range detection to detect specific interact objects, objects highlight function. Add a new state to control the interact action, use state machine to ensure the action exclusively each turn. Implement the feature to use click interact with object. Implment the feature to click on Object and use object to change edit the navmesh and block the ghost's path.

## W6

### Activity 1 
NEW: 
1. 1 new NPC with dialogue in the station scene,
2. mechanics of block ghost path by interact with specific object,
3. visualization of moving range,
4. visualization of round count,
5. Obstacle arragement in Hauntedhouse scene, Update of Navmesh,
6. visualization UI reminder of keys every time turn start,

Link: [Playtest Itch Page](https://tianchenglired.itch.io/sameghostnewplaytest)

Goals: 
1. Test whether visualizations are helpful for player to udnerstand what they could do in the hauntedhouse
3. Test whether obstacle arrangement could normally inlfuence both ghost's and
4. Test whether the pathfinding normally worked and bug free after Update the arrangement of the room
5. Test whether player can understand the task
6. Test whether block mechanics are bug free, and satsified the mechanics i expected

note:
1. people don't know how to control after they enter the hauntedhouse, the previous control system was abandoned when player entered the house,
2. more visualization of information in the game like the remained time, UI reminders of ghost's position and status and hint of how to control and move the player.
3. the game need more polished UI to understand their representation.
4. the game need better room design.
5. assgin more model in the game will make player easier to understand whats going on.
6.Bug need to be fix when player running out of ammo the shoot line will keep floating on the space.

### Activity 2
1. Because multiply mode in the blend multiply correspond number in each Vector, and the RGB channel are normally store the color as 0.0-1.0, when two color vector multiply there will be two decimals less than or equals 1 that multiply together in each number in the vector and the result must less than or equals to previous value and the less value represent darker color in this color logic or doesn't change if one of their value is Vector(1.0,1.0,1.0).
2. It will be more translucent, because Alpha just like color in RGB channel always store their value as 0.0-1.0, when use multiply to combine Alpha values there will be two decimals lees than or equals 1 that multiply together and the final value must be equals to or less than previous Alpha value, the less alpha value represent more transcluent, the smaller Alpha value makes the model more transcluent so it will be more transluent or does change if one of their value is 1.0.
3. When we creating SamplingTexture2D the unity will automatically use the UV map of the model which is using this graph and they get this from GPU. The data of every model will send to the GPU. The data of the model and specific data on shader graph that applied to the material are processed in the GPU together, the graph will find the model that are using this shader graph from material and find the correspond model data and its UV map on GPU. Shader receive those model information from GPU and find the UV map of the model to create UV0 node.
4. it is interesting, I notice that In the Blend node, every kinds of mode such as overlay, multiply and darken are different specfic algorithm that uses math to manipulate with math, which shows it is possible to achieve those different effect based on code which must be complicated. It is interesting to combine different algorithm to try different effect, it is interesting and exciting.

## W7

### Activity 1

1. the data for the Vertex Color node come from shiba mesh itself, in the shiba mesh it stored bunch of information of the model, the node get its color data from the mesh.
2. Because vertex color stored as data in each vertex in the mesh which means every vertex could store different color data, and the color of the faces are created by interpolate color data stored in the vertice of the faces. If color data in those vertices are different, interpolation will blended at the edges of different regions of color.
3. Because texture is a image, you can set any kind of size for your texture image(8192 * 8192), so it its detail based on how big your image is. But vertex color is actually blending or interpolating very color stored in different vertices on the face, so its based on how detailed your model is, how many vertices you got. I think vertex color could be use on any place that need interpolated like ground, using this will reduce workload, that you don't have to draw them all and also optimize the game.
4. After we use NormalDebug shader, the shader will set different color based on surface normal. And i notice that there is brighter part with different color with neighobor on the Shiba's back and is not smooth interpolated. That indicates the model wasn't smoothly processed at that part, it might protruding or facing elsewhere which makes the sudden change of direction of surface normal.
5. I can imagine that people testing the data of position of some specific model by using shader. Similar with normal debug, you just need to correspond RGB vector to position XYZ vector so different position will show different colors. I think it is helpful for people to clarify the position of each model for level designer, to helping them clarify created space by arragning models and adjust range of SFX effects. Also i think it clarify the height difference between positions to help designer adjust players ability of jump and movement ability value, like how far and height they can jump.
6. Because it uses a specific logic to calculate the light effect, they calculate the angle between light direction and model's surface normal, smaller the angle, the brighter it is. But in the case in the activity, the direction of light and surface normal are opposite or almost opposite, which always create huge obtuse angle between these two direction and that makes faces on the model that facing the light darker and not faces not facing the light are brighter. Thats the error.
7. Additive is more like lighten function in some art studio, it will transparent with a different function that change its color base on its background while transparenting so it would be brighter and more like a fire than Alpha mode.

## W8
### Activity 1 

New: 

1. Added a new text cutscene.
2. Updated level arrangement.
3. Created more art assets have been assigned to UIs.
4. Implemented level selection function
5. added more dialogue context, like cutscene texts.

Link: [SameGhostPlaytest3](https://tianchenglired.itch.io/sameghostplaytest3)

Playtesting Goals:
1. Test if level selection working normally.
2. Test if whole game progression is bug free.
3. Test if player could understand the gameplay and final goal based on UI and in-game scene, able to finished a game.
4. Test if player could understand the gameplay based on tutorial sheet.
5. Test if the difficulty of the game is suitable, whether the ghost is to weak or less.
6. Test if the game control is smooth.

Playtest Notes: 
put the model in it will be easier for player to understand what is going on,
change the color of the ghost when it get hit,
dialogue with commmander is confused, 
ammo UI is hard to noticed.
need a tutorial level, people always unable to understand how to interact with the door and dont want to read tutorial sheet.

### Activity 2

1. The pass called FullScreenPassRenderFeature, obviously from the name we can see that it represent the pass for our post-process effect which is also called full screen render feature. Other than that when you click on Draw Procedurals inside of this pass you can see the change of your post-process effect has been shown on the game scene, so i can clarify that this the pass associated with my post-process effect. 

2. When the lerp value is set to 0.5, the game scene will look like it mix the original scene with the post-process effect, it looks kinda transparency. When the lerp value is set to 0, the game scene will look exact like what original scene looks like without this post-process effect. When the lerp value is set to 1, the game scene will look like the post-process effect is fully applied in the game screen without any transparency.

3. I think the lerp value is represent the ratio that control how those two input values of post-process effect combine or mix each other, in this case, one of the input of lerp is same as original normal scene that without any effect, and another is value of that texture effect, so when you adjust the lerp value, you are adjust their mixing ratio, for example, when the it is 0.5, the algorithm should be like 0.5A + 0.5B, since one of the input are represent original scene, it will make lerp value similar with transparency ratio like alpha, and it will show same as answer in Q2.
  
4. From the graph of sin(time) i can see it y value is between -1 and 1, y value is the value input in the T in the lerp node which is accessible range is 0 to 1 so it can't process the y value of sin(time) between -1 to 0, but if we  use (sin(time)+1)/2, which made the value of y from -1 to 1 to 0 to 1 which means every y value of this algorithm could be used by lerp, and successfully achieve the smooth transition.

## W9
### Activity 1 

Game: PEAK

1. The object inside your bag will highlighted will you control your mouse to hover it. We think its pretty similar with the effect from W8 activity. The graph implement by get its normal vector and use multiply to increase its size, so you can get outline that bigger than model and covered it, then it changes the color of the outline color to achieve outline effect. It uses a specific method to detect whether mouse is pointing at that object by checking raycast from the mouse and activate it when it is pointing at the object.
2. Your model will  glowing when you are holding the gold bingbong statue. We think the shder are using fresnel effect that could make the model glowing, the shader will get the brightness of the character and multiply with fresnel and assign it to the model to make it brighter when holding it. The shader normaly is deactivated, they use a method to dectect whether the character is holding the statue, if they are holding set specific bool to true and shader will detect this bool activate its shader.

### Activity 2
<img width="678" height="407" alt="截屏2026-05-27 19 54 20" src="https://github.com/user-attachments/assets/fa6d2901-5d34-47ce-87d3-ad76f2189101" />

implemented the glowing effect on the ghost, the glowing color will change in time from red to green.


## W10
### Activity 1 

New: 

1. created AudioManager to control the SFX including walk, shoot, interact, talk, and button click.
2. 3 more new level design, whiteboxes are replaced by 3D assets and level selection function
3. multiple enemies and Blood UI tracking
4. magazine UI and mainmenu UI replaced by 3d assets and add more visualization
5. Blood bar interaction banned
6. gun trajectory fixed and visualization update
7. ghost and objects glowing shader


link: [SameGhostPlaytest4](https://tianchenglired.itch.io/sameghostfinaltest)

Goals:

1. test whether the AudioManager works well the whole game progression
2. test whether ghosts blood visualization works normally
3. test whether each level are bugs free and without any collider problems
4. test whether player can understand the whole game progression and game loop based on the tutorial sheet
5. test whether player understand and able to perform all functions that controls player, understand how to move shoot and interact with the door.
6. test whether multiple ghost level are bug free, without any bug due to the multiple ghost.


Notes: 

1. still hard to understand how to use the door
2. theres a bug of collider in the station scene
3. need bigger texts
4. player accident collide with the door collider and changed the scene
5. game loop not that clear, need sucess or lose hint
6. dont know how to interact with

### Activity 2

Our table come up with a specific strategy called object bubble diagram, we think it would be very helpful while we are on the planning stage. specifically, we break the game into different sections based on MVC model, separate a whole game loop in to different systems, visualization such as UI and animation and controllers that response the input. Create different bubble of objects which contains their attributes that will include in this game loop and separate them to diffferent section like system and visualization, etc. And then list every functions and features that will apply in this game, based on drawed object using arrows to build connection between each bubble and build a based logical structure of implement a specific fucntion. Personally, I like to sketch different scenes that inlcude in the game such as mainmenu, in game scene or end scene, etc so that i can also sketch my object bubble diagram based on sketches and MVC model.

This planning strategy will affect my socpe. Because the bubble diagram is a visualization of the my whole game structure. It separate my whole game loop in to small systems and connection to different objects and sections. It helps me calculate the scale and time use for implement different features, by looking bubble diagram and arrows as connection to different objects you can briefly estimate the scale of the whole game, briefly clarify your whole workload amount, so that you can adjust the scale of your game based on your time planning. Also, those visualization for features as arrows helps you prioritize your main mechanics, clarify the side or less important mechanics, that helps you distinguish which feature could be blocked then affect your scope.
