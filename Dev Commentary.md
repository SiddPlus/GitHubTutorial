## Project Outline

Developers and designers collaborate to enhance an existing game, originally created during a game jam. The game, titled *The Last Drop*, is being expanded with additional features and functionality to improve the player experience. Developers work on coding and integrating new mechanics, while designers focus on refining the user interface, visual elements, and overall aesthetic. By combining their expertise, both teams aim to create a more polished and engaging version of the game. The goal is to take the initial game jam concept and transform it into a more complete and playable experience, adding depth and replayability. With the developers focusing on technical improvements and the designers emphasizing user experience, the collaboration between these two roles ensures the game's growth and evolution. The end result will offer players a more immersive and enjoyable gameplay experience, showcasing the potential of *The Last Drop* beyond its original game jam prototype.

The goals and objectives for expanding The Last Drop after its game jam release are centered around enhancing the gameplay experience and refining the game's features. The primary goal is to improve the overall player experience by adding new mechanics, optimizing controls, and enhancing the game’s flow. Developers focus on addressing bugs and performance issues while introducing new content, such as new mechanics, to increase player enjoyability. Designers work on refining the game’s aesthetics, improving visual elements, level design, and ensuring the audio complements the gameplay. Accessibility is also a key goal. The collaboration between developers and designers is crucial for integrating technical improvements with a polished user experience. Performance optimization ensures smooth gameplay on multiple PC. Additionally, the team collects player feedback to guide adjustments and balancing. Ultimately, the objective is to release a more complete and engaging version of The Last Drop, showcasing the potential of the original game jam prototype.

One major challenge during the development of The Last Drop is time management. With the addition of new features, content, and mechanics, there’s a risk that the team may not meet the project’s deadline. The increased scope could lead to the hand in not being the teams vision if the team isn’t careful in managing resources and balancing priorities. Another challenge is communication, both between developers and designers and among developers themselves. Misunderstandings or lack of clear communication can result in mismatched expectations, missed details, or inconsistent implementation of game mechanics and design elements. This could affect the overall quality of the game, as both teams must be aligned in terms of goals and progress. Effective collaboration and regular check-ins will be essential to avoid these issues, ensuring that both technical and design elements come together smoothly. Overcoming these challenges will require careful planning, coordination, and adaptability to ensure the game is completed on time and meets the team's vision.

## Research

For this project, I conducted extensive research on FInterp To node and explored the Unreal Engine to create a more immersive experience. I prioritized studying official documentation to develop my ability to learn new techniques independently and without direct guidance.

Additionally, I used an example of an existing game to deepen my understanding of puzzle games mechanics and ensure its proper implementation within the game.

In this project, I studied Henry Jenkins' perspectives on video games as a 'lively art' to enhance my understanding of designing innovative, interactive, and emotionally resonant game experiences.

### Portal 2

Portal 2 is a critically acclaimed first-person puzzle-platformer by Valve that expands on its predecessor's innovative mechanics. Players navigate the Aperture Science facility using a Portal Gun, which creates linked portals for solving intricate puzzles. The game introduces new elements, such as repulsion, propulsion gels, and laser redirection, to add depth to the puzzles. With its rich narrative driven by the AI characters GLaDOS and Wheatley, the game weaves dark humor into a compelling story of corporate deception and experimentation. Portal 2 also features cooperative gameplay where two players work together to solve puzzles, emphasizing teamwork and communication. The game is celebrated for its clever design, gradual learning curve, and innovative integration of physics, making it a masterclass in puzzle-based game mechanics.

Portal 2’s development, discussed in GDC talks like *Creating a Sequel to a Game That Doesn’t Need One* (2012) (Portal 2: Creating a Sequel to a Game That Doesn’t Need One, 2016), highlights Valve’s innovative approach to expanding upon the original game’s mechanics. The team’s goal was to surprise players by evolving the core portal concept while introducing new gameplay elements like gels and laser redirection, which deepened the puzzle complexity. The narrative was enriched by a deeper exploration of GLaDOS, adding emotional weight and humor. The cooperative mode also stood out for its emphasis on teamwork and communication, requiring synchronized actions for puzzle-solving. Valve’s commitment to blending immersive storytelling with inventive mechanics resulted in a game that exceeded expectations, influencing puzzle-platformer design for years. These insights reflect Valve’s dedication to innovation in gameplay and narrative.

<iframe width="560" height="315" src="https://www.youtube.com/embed/BYFvwbby2YM?si=Wv3kc8FWwDYVWNtW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The insights from Portal 2’s design are highly applicable to my project, particularly in terms of gameplay mechanics and player engagement. Valve’s approach to gradually introducing new mechanics—ensuring players understand and feel competent before adding complexity—aligns with my goal of creating an intuitive learning curve for players. This philosophy of starting simple and progressively increasing challenge allows players to feel confident and engaged. By prioritizing player experience and a gradual challenge progression, I’m aiming to make sure players stay immersed in the game without feeling overwhelmed. These principles influence my decision-making by guiding the pacing of new features and mechanics, ensuring that players can develop their skills at a steady and rewarding pace.

### Unreal Engine 5 FInterp To Documentation

The documentation on FInterpTo in Unreal Engine provides valuable insight into interpolating values, which is especially relevant for The Last Drop, where smooth transitions are key to a polished player experience. FInterpTo allows for gradual movement from a start value to a target value, with inputs including the current value, target value, delta time (for frame rate smoothness), and interpolation speed. In The Last Drop, this can be used to smoothly interpolate the bubble’s size when it collides with water. This creates a natural effect, ensuring that the bubble grows and shrinks gradually and responsively. It enhances puzzle-solving by providing consistent visual feedback, making player actions more intuitive. Interpolating the bubble’s size ensures smooth, continuous transitions rather than abrupt changes, contributing to a polished mechanic and a more engaging, immersive player experience.

The technical knowledge from the FInterpTo documentation supports my project work on The Last Drop by providing a method for creating smooth, responsive transitions, particularly with the bubble growth and shrinkage mechanic. By applying FInterpTo, I can ensure the bubble's size changes gradually and naturally when it collides with water, making the transition feel more polished and visually appealing. This enhances the puzzle-solving experience by making player actions more intuitive and engaging. The knowledge guides my decision-making by offering a tool to fine-tune the speed and smoothness of these transitions, ensuring they align with the overall aesthetic and gameplay goals. Using FInterpTo contributes to a more fluid and immersive player experience, improving gameplay clarity, visual feedback, and player satisfaction. It helps create a seamless, polished interaction that strengthens the core mechanics of the game.



### Academic Source

Henry Jenkins, in his essay "Games, the New Lively Art" positions video games as a significant art form in the digital age, akin to how cinema and jazz were regarded during the machine age. He notes that games "open up new aesthetic experiences" (Jenkins, 2007, p. 23),emphasizing their capacity to transform the computer screen into a platform for accessible experimentation and innovation, engaging players in unique and meaningful ways. Jenkins draws parallels between the skepticism faced by early cinema and that encountered by contemporary video games, suggesting that, like films, games have the potential to evoke deep emotional engagement. He emphasizes that achieving such engagement doesn't necessarily rely on realism; instead, it hinges on the unique capabilities of the medium. He references Steve Poole's assertion that while film is "tied down to real spaces" (Jenkins, 2007, p. 39), video games possess "limitless plasticity" (Jenkins, 2007, p. 39), allowing for unprecedented artistic expression. Jenkins advocates for game designers to embrace this flexibility, encouraging them to create novel environments that captivate and immerse players. He cautions against merely transplanting cinematic techniques into games, arguing that such practices can lead to products "lacking meaningful gameplay" (Jenkins, 2007, p. 39). By recognizing and harnessing the distinct properties of video games, designers can craft experiences that are both innovative and emotionally resonant. By acknowledging video games as a "lively art" (Jenkins, 2007, p. 40), Jenkins challenges traditional distinctions between high and low culture, advocating for a broader appreciation of interactive media's role in the arts. This perspective encourages designers to explore the full expressive potential of games, pushing the boundaries of storytelling, aesthetics, and player engagement. 

## Impleamentation

### BP Spinning Actor

#### Initial Blueprint

<iframe width="560" height="315" src="https://blueprintue.com/render/3843iie5/" scrolling="no" allowfullscreen></iframe>

This blueprint rotates a static mesh over time. The Event BeginPlay node starts a Delay before calling Start Spin. Start Spin sets a looping timer (Set Timer by Event) to run the spin logic every 6 seconds. The rotation logic gets the mesh’s current relative rotation and modifies it using Lerp (Rotator) to interpolate between the current and target rotation (90-degree roll adjustment). SetRelativeRotation applies the update. A timeline named Spin manages animation, ensuring a gradual transition rather than an abrupt movement, creating a smooth and continuous spinning effect.

#### Actor Component

<iframe width="560" height="315" src="https://blueprintue.com/render/i6g12nxs/" scrolling="no" allowfullscreen></iframe>

This blueprint improves rotation handling with a structured, modular approach. Instead of modifying rotation in a single event, it uses a collapsed node for dynamic calculations. This node takes input parameters (rotation axes, time, and multipliers) and outputs refined values, enhancing interpolation control. The main event graph calls this function to compute new rotation values before applying them via SetActorRotation, ensuring smoother transformations. Compared to the first blueprint, this design enhances reusability, maintainability, and scalability, making it easier to adjust rotational behavior without modifying core logic.

### Bubble Size Change

#### Growth Function

<iframe width="560" height="315" src="https://blueprintue.com/render/5ng9to-u/" scrolling="no" allowfullscreen></iframe>

This function manages bubble growth using "Water Amount." The "Growth" function adds it to "Current Size" and updates it with a SET node. If "Current Size" meets or exceeds "Max Size," it is clamped using another SET node, preventing overexpansion while allowing dynamic growth in response to game interactions. This ensures controlled and realistic size changes.

#### Shrink Function

<iframe width="560" height="315" src="https://blueprintue.com/render/q0y2cgzq/" scrolling="no" allowfullscreen></iframe>

This function manages bubble shrinking based on size and water amount. The "Shrink" function checks if "Current Size" is below "Max Size." If true, it reduces "Current Size" using "Water Amount" and updates it. A second check ensures it doesn’t fall below "Min Size," clamping if necessary. This prevents excessive shrinking while maintaining controlled, dynamic size changes.

#### Growth Shrink Logic

<iframe width="560" height="315" src="https://blueprintue.com/render/w96ui2nl/" scrolling="no" allowfullscreen></iframe>

This mechanic updates every frame using Event Tick, storing Delta Seconds for size changes in the "GrowthShrink" node. A Branch checks if the object is in water, triggering the Growth or Shrink function based on the condition. Lerp nodes handle smooth scaling transitions, and FInterp To interpolates the sphere’s scale, adjusting it dynamically based on water interaction for consistent, fluid transformations.

## Outcome

## Reflection

### Research Effectiveness

The research conducted significantly enhanced *The Last Drop* by refining technical mechanics, gameplay design, and artistic direction. Studying FInterpTo allowed for smoother transitions, particularly with bubble mechanics, improving fluidity. Insights from Portal 2 guided the development of an intuitive learning curve, ensuring players were engaged without feeling overwhelmed. Henry Jenkins’ perspective on video games as a unique, emotionally resonant art form enriched the design, helping to deepen player engagement and elevate the narrative. The Unreal Engine FInterpTo documentation and Portal 2’s design philosophy had the most significant impact on the project, directly influencing both technical implementation and gameplay structure. A research gap in the project lies in user testing for gameplay flow, accessibility design, and performance optimization, as well as improving collaborative workflows.

### Positive Analysis



### Negative Analysis



### Next Time

If I were to undertake a similar project again, I would integrate more C++ into programming the game mechanics for greater control and efficiency. I would focus on using C++ for core systems and performance-critical features, such as physics and AI, to optimize the game's performance. Planning the game architecture with C++ in mind from the start would allow better management of complex systems, and the ability to handle low-level operations more effectively. I’d improve communication between C++ and Blueprint to maintain flexibility while benefiting from both approaches. Additionally, leveraging Unreal Engine’s C++ capabilities for smart pointers and memory management would create more scalable systems. Designing modular and reusable C++ code would also ensure smooth development for future projects.

## Bibliography

Porrtal 2 (PC (Steam)) (2011) Developed and published by Valve

Portal 2: Creating a Sequel to a Game That Doesn’t Need One (2016) At: https://www.youtube.com/watch?v=BYFvwbby2YM

FInterp To | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation/FInterpTo

Henry Jenkins (2007). The WOW Climax: Tracing the emotional impact of popular culture, New York: NY, New York University.