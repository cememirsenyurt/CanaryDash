# CanaryDash
Challenging Navigation Game of Flying Canary Over Obstacles

Introduction

•	This document outlines the development process for the "Canary Dash" game, a variant of the popular Flappy Bird, tailored with unique assets and mechanics. The game development cycle encapsulated with details below. The creation and integration of game components using Unity and C#, from initial asset design to gameplay mechanics and UI implementation.

Asset Creation and Integration

•	Designing Game Assets: The initial phase involved creating the visual assets required for the game. A canary and a stone pipe were designed using digital art tool called DALL-E 3 (Chat GPT). Post-design, Adobe software was utilized to remove the backgrounds from these images, ensuring they could be seamlessly integrated into the game's environment transparently without any visual discrepancies.

•	Incorporation into Unity: The canary asset was then imported into Unity. It was placed within a 2D space and resized appropriately to fit the game's scale. To enhance realism and gameplay dynamics, the canary was converted into a physics-enabled object. This modification allowed the canary to interact with the game's gravity, ensuring it would descend over time unless counteracted by the player's inputs.

Game Mechanics and Scripting

•	Flight Mechanics: A custom C# script was developed to govern the canary's flight within the designated play area. This script was designed to detect spacebar presses, enabling the canary to fly against the physical gravity and ascend. The delicate balance of flight mechanics necessitated careful tuning to ensure a challenging yet responsive gameplay experience.

•	Obstacle Design and Movement: The stone pipe asset was utilized to create the primary obstacles within the game. A 'mother pipe' object was established first. Then, with child objects representing the top and bottom components of the pipes. Another C# script was applied to these objects to enable horizontal movement across the screen, simulating the continuous flow of obstacles the player must navigate.

User Interface and Game Progression

•	Score Tracking: An integral part of the game is the scoring system, implemented as a UI element within the Unity environment. This system awards players a point for each set of pipes successfully navigated, encouraging continuous play and skill improvement.

•	Game Over Mechanics: To increase stakes and add a layer of difficulty, a game over condition was established. When the player collides with a pipe, the game immediately stops taking further input detection, effectively ending the current gaming session. A UI element then prompts the player with the option to restart the game, allowing for quick re-entry into the gameplay loop.

Conclusion

•	The development of "Canary Dash" represents a comprehensive approach to game design, utilizing both artistic and technical skills to create an engaging gameplay experience. Through careful asset creation, scripting, and UI design, the game offers a challenging yet accessible experience for players, emphasizing skill progression. This document serves as a detailed record of the game's development process, highlighting the integration of various components and mechanics that contribute to the final product.

What I've gained

I was already familiar with Object-Oriented Design but had never tried C# before. So, I quickly learned the basics of C# in a day, then got to grips with the Unity platform and learned how to use it. Inspired by the basic concept of "Flappy Bird," I created "Canary Dash."

What else could have been done to the game

•	New gameplay elements could have been introduced, such as the canary shooting arrows at buttons to open closed pipes.
•	A sound system could have been integrated to play a sound every time the player gains points.
•	The background could have been made more interactive by adding elements like clouds and the sun.
•	A system to track the highest score and a welcome page script could have been added.
•	Lastly, difficulty levels could have been introduced to vary the pace and the gap between pipes, allowing for player competition. 

NOTE: Currently, in the first version, there is one problem with the game. You must start directly with a space press to hold the bird in the game.  In the next versions this bug will be gone easily.
