# fall-semester-reflection


## Question 1: What did you accomplish this semester? 
Please list all the projects / assignments you've completed

- I've worked on creating a video game using Unity. The original idea was to join a Game Jam that lasted only 3 days, but creating the game took much longer than I thought it would. I had set out with the idea of creating a game with a map that contains itself and to make a player and enemies that can scale with the size of the map as they travel along it. I feel that I've really advanced my coding skills and knowledge of C#.


## Question 2: What are 2-3 major issues you ran into?
Please describe 2-3 issues you ran into, how you resolved them and what you learned from them?

- The first major issue I had was getting the map to create larger and smaller copies of itself that were placed in the correct location. I spent hours writing code that would work for any map given the maps dimensions, but the maps kept going in not quite the correct place or with the correct scaling. There were a few things that helped me fix this issue. The first thing was relizes that the center of the prefab of the test map I was using wasn't actually at the center, but at a corner of the map. This made the local-space location of the map different from what I assumed it was, and fixing this fixed my problems.
-  The next major issue I had was with the Navigation Mesh, a feature of Unity that helps with pathfinding and grounding. The first issue with the NavMesh was that I needed it to generate after the play button was pressed instead of in the editor since the map generates at runtime. I solved this by learning in depth how to create NavMeshs with code instead of automatically. The next problem was how to get the NavMesh working with an ever changing map, since as you go inwards/outwards, layers of the map get deleted/generated. To reduce processing time, instead of creating entirely new NavMesh's for new layers, I just reused already excisting NavMeshs. The next 2 problems I had were that the NavMeshes weren't generating correctly as the map got smaller and the NavMeshes of each layer of the map weren't connected. I solved both these issues by deep diving into the code and figuring out how to use Nav Mesh Agents for the Mesh generation and how to generate Nav Mesh Links at edges of NavMeshes that were close enough to eachother.

## Question 3: What advice do you have for yourself for next semester? 
What do you want to accomplish / how might you change your work habits next semester.

- I would like to keep working on the game that I have since I now have a good foundation to build an actual game from. I've learned this semester that I shouldn't always try to solve coding problems on my own. I've had many times where I've spent hours struggling to solve a problem only for someone (Mx. Collard) to know a solution. A habit that I have when coding is to code for hours at a time, but I'm going to change this. I know that I get burned out and worse at coding when I code for hours at a time, so this next semester I'm going to force myself to take breaks from coding every now and then to prevent this. I also won't spend so much time procrasti-coding on my other school work so I don't have a bunch of work that I have to do the night before it's due.
