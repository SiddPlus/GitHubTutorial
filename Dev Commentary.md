## Project Outline

Developers and designers are collaborating to expand *The Last Drop*, a game originally created during a game jam, by enhancing its features, functionality, and overall player experience. A key goal is to ensure smooth gameplay across various PCs and to incorporate player feedback for balanced improvements. However, challenges like time management and communication pose risks to meeting deadlines and maintaining the team’s vision. Clear collaboration, regular check-ins, and resource planning are essential for delivering a high-quality, cohesive game.

## Research

### Methodology

For this project, I conducted extensive research on `FInterpTo`, `CombineRotators` and Enhanced Input nodes and explored the Unreal Engine to create a more immersive experience. I prioritized studying official documentation to develop my ability to learn new techniques independently and without direct guidance. Additionally, I used an example of an existing game which is Portal 2 to deepen my understanding of puzzle games mechanics and ensure its proper implementation within the game. In this project, I studied Henry Jenkins' perspectives on video games as a 'lively art' to enhance my understanding of designing innovative, interactive, and emotionally resonant game experiences.

The research profoundly shaped The Last Drop’s development by blending design inspiration, technical application, and theoretical grounding. Portal 2 informed the project’s gradual learning curve, physics-based puzzles, and seamless integration of narrative and humor—guiding intuitive progression and immersive gameplay. Valve’s emphasis on player experience and team collaboration resonated with our own development goals. Technically, Unreal Engine 5 documentation on `FInterpTo`, `CombineRotators`, and Enhanced Input enabled smooth transitions, responsive controls, and polished mechanics—enhancing accessibility and visual coherence. Academic perspectives from Jenkins, Kirkpatrick, and Kant framed games as expressive, interactive art forms. Their insights reinforced our focus on gameplay over cinematic mimicry and emphasized emotional resonance through form and interactivity. This holistic understanding helped us elevate The Last Drop beyond its game jam origins, embracing innovation, clarity, and player agency. Overall, the research provided a foundation for designing a cohesive, meaningful experience that balances creativity, usability, and engagement across disciplines.

### Portal 2

Portal 2’s (Valve Corporation (2011) Portal 2 [video game]. Bellevue, WA: Valve.) gradual learning curve, physics-based puzzles, and seamless narrative integration will offer valuable insights for The Last Drop. Like Portal 2, The Last Drop will introduce mechanics progressively, ensuring intuitive player learning. Physics-driven interactions, such as bubble growth, will be refined for engaging gameplay. Additionally, Portal 2’s blend of humor and storytelling will enhance immersion, serving as a model for *The Last Drop*. The cooperative aspects of Portal 2 will highlight the importance of communication, mirroring *The Last Drop*’s development challenges, where clear coordination will ensure a cohesive and polished final product.

Portal 2’s development, discussed in GDC talks like Creating a Sequel to a Game That Doesn’t Need One (2012) (Portal 2: Creating a Sequel to a Game That Doesn’t Need One, 2016), showcases Valve’s innovation in evolving gameplay mechanics and storytelling. Similarly, The Last Drop will build upon its game jam roots, refining core mechanics and introducing new elements to increase complexity. Like Portal 2’s use of gels and laser redirection, The Last Drop will evolve its physics interactions. Valve’s blend of humor, narrative, and teamwork in Portal 2 will guide The Last Drop’s approach, ensuring a cohesive, innovative, and immersive player experience.

<iframe width="560" height="315" src="https://www.youtube.com/embed/BYFvwbby2YM?si=Wv3kc8FWwDYVWNtW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

*Figure 1*: Portal 2 GDC talk

The insights from *Portal 2*’s design are highly applicable to *The Last Drop*’s development, particularly regarding gameplay mechanics and player engagement. Valve’s method of gradually introducing new mechanics—allowing players to understand and feel competent before adding complexity—aligns with my goal of creating an intuitive learning curve. This approach ensures players stay confident and engaged while progressively increasing the challenge. By prioritizing player experience and gradual progression, I aim to keep players immersed without feeling overwhelmed. These principles guide my decisions on pacing new features, ensuring a steady, rewarding skill development curve for players.

![Portal 2](https://raw.githubusercontent.com/SiddPlus/GitHubTutorial/refs/heads/main/Photos/1449-2011-07-04_00012.jpg)

*Figure 2*: Drop Splash Mechanic from Portal 2

### Unreal Engine 5 Documentations

The documentations on `FInterpTo`, `CombineRotators`, and Enhanced Input in Unreal Engine offers critical insight into implementing smooth transitions, seamless rotations, and responsive controls—key elements that will significantly enhance The Last Drop. `FInterpTo`  will be used to interpolate the bubble’s size when it collides with water, creating natural growth and shrinkage that provides intuitive visual feedback and ensures a polished, immersive experience. Similarly, `CombineRotators` will be leveraged to blend rotational values, powering rotating platforms and objects to create smooth, infinite spinning effects that enhance navigation and puzzle complexity while maintaining visual cohesion and performance consistency across devices. Enhanced Input will provide a modern, flexible input system that supports context-sensitive mappings and diverse input devices, ensuring accessible, responsive controls that cater to player preference and hardware variation. Together, these tools support the project’s goals of creating a polished, dynamic, and inclusive player experience while enabling efficient development and design collaboration.

The technical knowledge from the `FInterpTo`, `CombineRotators`, and Enhanced Input documentations in Unreal Engine will play a crucial role in supporting my project work on *The Last Drop* by enabling smoother transitions, fluid rotations, and responsive control systems. Applying `FInterpTo` will allow for gradual, natural changes in the bubble’s size when it collides with water, enhancing the visual polish and making player interactions feel intuitive and engaging—key to improving gameplay clarity and puzzle-solving satisfaction. Similarly, using `CombineRotators` will ensure smooth, continuous rotations for platforms and environmental elements, elevating the overall immersion and navigation while maintaining visual and mechanical consistency across hardware setups. Enhanced Input will provide a flexible, modular system for managing diverse control schemes, ensuring accessible, consistent input support for keyboards, mice, and controllers. This system will guide efficient collaboration between developers and designers while allowing for scalable input logic that adapts to feedback and design evolution. Together, these tools will strengthen core mechanics, contribute to a polished and immersive experience, and help deliver a professional-quality game aligned with both technical standards and player expectations.

![FInterpTo](https://raw.githubusercontent.com/SiddPlus/GitHubTutorial/refs/heads/main/Photos/FInterpTo.png)

*Figure 3*: `FInterpTo` Node

![FInterpTo](https://raw.githubusercontent.com/SiddPlus/GitHubTutorial/refs/heads/main/Photos/CombineRotators.png)

*Figure 4*: `CombineRotators` Node

![FInterpTo](https://raw.githubusercontent.com/SiddPlus/GitHubTutorial/refs/heads/main/Photos/Input.png)

*Figure 5*: Enhanced Input Action Node for Gamepad

### Academic Sources

In his essay "Games, the New Lively Art," Henry Jenkins asserts that video games are poised to become a significant art form in the digital era, paralleling the recognition that cinema and jazz received during the machine age. He observes that games "open up new aesthetic experiences" (Jenkins, 2007, p. 23), transforming the computer screen into a platform for accessible experimentation and innovation. This perspective underscores the potential of video games to serve as dynamic art forms, engaging players in unique and meaningful ways. Graeme Kirkpatrick, in his work "Aesthetic Theory and the Video Game," further elucidates this concept by stating, "Aesthetic experience occurs when we find something is pleasing to us by virtue of its form. Such an object stimulates us in the sense that it provokes and incites a feeling response but does so in a way that goes beyond merely being pleasing to the eye… it amplifies our sense of ourselves as free moral agents" (Kirkpatrick, 2011, p. 23). Immanuel Kant also emphasizes the subjective nature of beauty, noting that "Apart from the relation to the subject’s feeling, beauty is nothing by itself." (Kant, 1987, p. 219). Applying these insights to the development of "The Last Drop," a game initially created during a game jam, highlights the importance of leveraging the unique capabilities of the gaming medium. The collaboration between developers and designers to introduce new mechanics, refine visual elements, and enhance the overall player experience embodies the spirit of experimentation and innovation that Jenkins emphasizes. By embracing the "limitless plasticity" (Jenkins, 2007, p. 39) of video games, the team can craft novel environments and interactions that captivate and immerse players. Jenkins also cautions against merely transplanting cinematic techniques into games, arguing that such practices can lead to products "lacking meaningful gameplay" (Jenkins, 2007, p. 39). This insight is particularly relevant for "The Last Drop" team, emphasizing the need to focus on interactive elements that distinguish games from other media. By recognizing and harnessing the distinct properties of video games, the developers and designers can create an experience that is both innovative and emotionally resonant. This approach will not only enhance the overall player experience but also align with the broader recognition of games as a legitimate and impactful art form in contemporary culture.

## Impleamentation

### BP Spinning Actor

#### Initial Blueprint

<iframe width="560" height="315" src="https://blueprintue.com/render/3843iie5/" scrolling="no" allowfullscreen></iframe>

*Figure 6*: This Blueprint rotates a static mesh smoothly over time by using a timeline named *Spin* to animate a 90-degree roll adjustment; triggered on *Event BeginPlay* after a delay, it calls *Start Spin*, which sets a looping timer (every 6 seconds) that uses *Lerp (Rotator)* to interpolate from the current to target rotation, then applies it with *SetRelativeRotation* for a continuous spinning effect.

#### Actor Component

<iframe width="560" height="315" src="https://blueprintue.com/render/i6g12nxs/" scrolling="no" allowfullscreen></iframe>

*Figure 7*: This Blueprint enhances rotation handling through a modular approach by using a collapsed node that takes input parameters (axes, time, multipliers) to output refined values, enabling smoother interpolation and reusability; the main event graph calls this node before applying the result with *SetActorRotation*, improving maintainability and scalability over the original design.

### Bubble Size Change

#### Growth Function

<iframe width="560" height="315" src="https://blueprintue.com/render/5ng9to-u/" scrolling="no" allowfullscreen></iframe>

*Figure 8*: This function controls bubble growth by adding *Water Amount* to *Current Size* via a *Growth* function, updating it with a *SET* node and clamping it when it reaches *Max Size*, ensuring dynamic yet controlled and realistic size changes during gameplay.

#### Shrink Function

<iframe width="560" height="315" src="https://blueprintue.com/render/q0y2cgzq/" scrolling="no" allowfullscreen></iframe>

*Figure 9: This function manages bubble shrinking by checking if *Current Size* is below *Max Size*, then reducing it by *Water Amount* and updating it, with a second check to clamp it at *Min Size* if needed—ensuring controlled, dynamic size changes without excessive shrinking.

#### Growth Shrink Logic

<iframe width="560" height="315" src="https://blueprintue.com/render/w96ui2nl/" scrolling="no" allowfullscreen></iframe>

*Figure 10*: This mechanic runs every frame via *Event Tick*, storing *Delta Seconds* in the *GrowthShrink* node; a *Branch* checks water interaction to trigger *Growth* or *Shrink*, while *Lerp* and *FInterp To* ensure smooth, dynamic scaling transitions for fluid, responsive transformations.

### Testing

Once I completed development on a mechanic, I shifted my focus to thoroughly testing it to ensure that it functioned correctly and delivered a smooth, consistent experience. I began by running tests directly within the editor, which allowed me to observe the mechanic’s behavior in a controlled setting and pinpoint any bugs or unintended outcomes. This early testing phase was critical for identifying issues before integration into broader gameplay. I paid close attention to how it interacted with other systems, assets, and variables, ensuring it behaved as expected in a range of situations. To support this, I created an agile testing table where I documented bugs, tracked fixes, and noted any dependencies or side effects. This table served as a visual guide for iterative development, helping me prioritize tasks and maintain clarity throughout each cycle of testing. During the process, I made a series of adjustments—some were minor, such as tweaking values or modifying collision settings, while others required reworking logic or restructuring scripts to improve overall stability and performance. I continuously approached the mechanic from both a technical and player-centric perspective, asking whether it felt intuitive, engaging, and balanced within the gameplay loop. I also evaluated how it contributed to pacing, difficulty, and player agency. After each revision, I returned to the testing table to log outcomes, reflect on changes, and reverify existing functionality. This cycle of feedback and refinement was repeated until I reached a version that felt polished and dependable. The final mechanic functioned seamlessly, elevating the quality of the gameplay experience and integrating naturally into the game’s broader system.

| Test | Test Case | Test Steps | Actual Result | Expected Result | Outcome | Solution |
|------|-----------|------------|----------------|------------------|---------|----------|
| The gears in the environment and rotating platforms must spin forever | TC01: To confirm the gears and rotating platforms spin continuously upon starting the game | Start game | Gears and rotating platforms only rotate once | Gears and rotating platforms spin forever | Fail | Use `CombineRotators` node instead of normal Rotator node |
|  | TC02: To confirm the gears and rotating platforms spin continuously upon starting the game | Start game | Gears and rotating platforms spin forever | Gears and rotating platforms spin forever | Pass | — |
| As a bubble char, when it collides with water it should grow in size up to its max | TC01: To check if the bubble char grows in size up to its max if it is colliding with water | Start game<br>Player presses left click<br>Bubble moves towards water<br>Bubble collides with water | Bubble doesn’t grow in size when colliding with water | Bubble grows in size up to its max when colliding with water | Fail | Use `BPI Interact` and `OnComponentBeginOverlap` to handle the collision not just the `OnComponentBeginOverlap` |
|  | TC02: To check if the bubble char grows in size up to its max if it is colliding with water | Start game<br>Player presses left click<br>Bubble moves towards water<br>Bubble collides with water | Bubble grows in size up to its max when colliding with water | Bubble grows in size up to its max when colliding with water | Pass | — |
| As a bubble char, when it collides with water it should shrink in size up to its min | TC01: To check if the bubble char shrinks in size up to its min if it is not colliding with water | Start game<br>Player presses left click | Bubble shrinks in size up to its min if it is not colliding with water | Bubble shrinks in size up to its min if it is not colliding with water | Pass | — |
| Player clicks on buttons in the main menu | TC01: To check if player is able to click the buttons in the main menu | Start game | Mouse rejects hovering over the buttons | Player is able to press the buttons in the main menu | Fail | Check if the player is not in the main menu and not in UI mode. If both are true, allow right stick input from a gamepad to control the mouse cursor position via the `Set Mouse Location` |
|  | TC02: To check if player is able to click the buttons in the main menu | Start game | Player is able to press the buttons in the main menu | Player is able to press the buttons in the main menu | Pass | — |
| If player spawns in main menu | TC01: To check if player character doesn’t spawn in main menu level | Start game | Player character spawns in main menu level | Player character doesn’t spawn in main menu level | Fail | Replaced the player character with a temporary player pawn specifically for the main menu level |
|  | TC02: To check if player character doesn’t spawn in main menu level | Start game | Player character doesn’t spawn in main menu level | Player character doesn’t spawn in main menu level | Pass | — |

*Figure 11*: Agile Testing Table

### Technical Difficulties

I assisted a designer in pushing their work and the rive plugin to the GitHub main branch. When they initially pushed their work to main, it caused their changes to be deleted. To prevent this from happening, I carefully removed the conflicting changes before pushing their work to the main branch. Additionally, I addressed an issue with player spawning in the main menu by replacing the player character with a temporary player pawn specifically for the main menu level. This temporary pawn poses the player, which successfully resolved the spawning issue. By performing these tasks, I was able to help stabilize the project, ensuring that both the player's experience and the designer's workflow were smooth. These fixes significantly improved the game's functionality, allowing the project to move forward without the issues that had been previously hindering it.

#### Mouse Controller UI Bug

<iframe width="560" height="315" src="https://blueprintue.com/render/d_zsda8w/" scrolling="no" allowfullscreen></iframe>

*Figure 12*: The bug was the player was not able to click the buttons in the main menu

#### Mouse Controller UI Bug Fix

<iframe width="560" height="315" src="https://blueprintue.com/render/7bo4mxqu/" scrolling="no" allowfullscreen></iframe>

*Figure 13*: I connected the right thumbstick axis from the gamepad and checked if the current level wasn’t the main menu. If it wasn’t, I ensured that the mouse position was set correctly, which eliminated the glitch.

## Outcome

- [Outcome Repository](https://github.com/University-for-the-Creative-Arts/The-Last-Drop)

*Link 1*: Link to Github Repository of The Last Drop project

- [Outcome Build](https://ucreative-my.sharepoint.com/:f:/g/personal/2303759_students_ucreative_ac_uk/Ek9txoh-EL9JnQtqCSUUB3cBo0-nmzBKndsqdi7A8DIk8g?e=Xf6GKY)

*Link 1*: Link to build of The Last Drop project

- [Game Trailer](https://www.youtube.com/watch?v=ce3V-rcXZjs)

*Link 1*: Link to YouTube video of The Last Drop project trailer

## Reflection

### Research Effectiveness

The research conducted for The Last Drop provided essential insights from Portal 2, Unreal Engine 5 documentation, and academic sources, significantly influencing the game’s development. Portal 2's gradual learning curve and physics-based puzzles directly inspired the design of intuitive, progressive mechanics, ensuring that players could master simple tasks before facing more complex challenges. The documentation on Unreal Engine 5 tools like FInterpTo, CombineRotators, and Enhanced Input was crucial in creating smooth transitions, fluid rotations, and responsive controls, enhancing the overall gameplay experience. Academic sources, such as Jenkins and Kirkpatrick, emphasized the importance of interactivity and aesthetics, influencing the game’s design philosophy. However, gaps in player feedback and puzzle complexity were identified. Addressing these could have further refined puzzle dynamics, enhanced player engagement, and made the experience more polished.

### Positive Analysis

Working in a large team gave me valuable experience that will benefit me in future professional environments. Collaborating with individuals from diverse backgrounds allowed me to appreciate different perspectives and skill sets. I quickly learned the importance of clear and consistent communication, as coordinating with a large group required ongoing discussion and alignment. This experience also helped me understand how to function within a structured environment, where tasks were divided, deadlines were strict, and collaboration was essential. I developed a stronger ability to balance my individual responsibilities with the team’s overall goals, ensuring that my contributions aligned with group objectives. Adaptability became crucial, as priorities and tasks often shifted. I became more flexible and better at adjusting to change. Working through challenges with such a varied team also strengthened my problem-solving skills, as it required creative thinking and collaboration. Regular feedback helped me refine my skills and understand how to navigate team dynamics more effectively. Exposure to a range of working styles and problem-solving approaches was incredibly enriching. Overall, this experience has been a significant step in both my personal and professional development. It has prepared me to contribute meaningfully to future collaborative environments and work efficiently as part of any team.

### Negative Analysis

The project's coordination and communication were poorly managed, leading to significant challenges throughout the process. There was a lack of clarity regarding roles and responsibilities, which caused confusion and led to duplicated efforts—or in some cases, important tasks being overlooked altogether. Deadlines were frequently missed, with minimal follow-up to ensure progress. Without a clear communication structure, important updates and decisions were often not shared, leaving team members unaware of project changes or overall status. This lack of transparency created frustration and made collaboration difficult. Additionally, feedback was not always communicated in a timely manner, resulting in last-minute scrambles to meet expectations. The project management tools available were underutilized, and there was no consistent method for tracking progress or resolving issues. These shortcomings negatively impacted the project's efficiency and overall quality, with problems often being identified too late to address properly. However, this experience clearly highlighted the importance of effective communication, defined roles, and structured project management. Moving forward, I now understand how essential these elements are to a project's success and the cohesion of a team.

### Next Time

If I were to undertake a similar project again, I would incorporate more C++ into the development of core game mechanics to gain greater control and optimize performance. Specifically, I’d use C++ for systems that are performance-critical—such as physics calculations and AI behaviors—to improve efficiency and scalability. Planning the game architecture with C++ in mind from the outset would allow for better management of complex systems and more effective handling of low-level operations. I would also improve the integration between C++ and Blueprints to maintain both performance and flexibility throughout development. Additionally, leveraging Unreal Engine’s C++ features, such as smart pointers and more robust memory management, would support cleaner, more maintainable code. By designing modular and reusable C++ components, future development would be smoother and more efficient. I also plan to explore automated testing and debugging tools in C++ to catch issues earlier in development. Overall, this approach would not only enhance technical performance but also contribute to a more professional and scalable development process.

## Bibliography

Porrtal 2 (PC (Steam)) (2011) Developed and published by Valve

Portal 2: Creating a Sequel to a Game That Doesn’t Need One (2016) At: https://www.youtube.com/watch?v=BYFvwbby2YM

FInterp To | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation/FInterpTo

Henry Jenkins (2007). The WOW Climax: Tracing the emotional impact of popular culture, New York: NY, New York University.