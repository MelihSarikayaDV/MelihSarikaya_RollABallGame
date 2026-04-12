# Roll a Ball - Game Development Diary

## Project Overview
This is my midterm project based on the Unity Learn "Roll a Ball" tutorial. I completed all the required steps and successfully uploaded the project to GitHub.

## Completed Steps
1. Setting up the game
2. Moving the player
3. Moving the camera
4. Setting up the play area
5. Creating collectibles
6. Displaying Score and Text 
7. Adding Enemy AI Navigation 

## What I Learned
* **Git & GitHub:** I learned how to use a ".gitignore" file to avoid uploading large, unnecessary files like the "Library" folder. I also learned how to save my progress step by step using meaningful commits.
* **Player Movement:** I learned how to use the Unity Physics system. I added a "Rigidbody" component to the ball and used the "Input" system to move it by applying force.
* **Camera Movement:** I learned that the camera tracking code must be placed inside "LateUpdate()" instead of "Update()". This prevents the camera from shaking (jittering) while following the player.
* **Collectibles:** I learned how to create "Prefabs" to easily duplicate items. I also used the "Is Trigger" option on the colliders so the player can pass through and collect the cubes using the "OnTriggerEnter" code.
* **UI (User Interface):** I used "TextMeshPro" to create a working UI system that displays the collected score and a "You Win!" message when the game is over.
* **Enemy AI:** I learned the basics of Unity's NavMesh system. I baked the ground and used a "NavMesh Agent" to make an enemy follow the player around the map.

## Visual Improvements (Bonus)
To make the game look more interesting than a standard gray prototype, I created custom "Materials". I added distinct colors to the ground and the player object to improve the visual experience.

## File Organization
I kept my Unity project clean and organized. All assets are correctly placed in their respective folders: "Scripts", "Scenes", "Materials", and "Prefabs".