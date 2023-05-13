A simple adventure game by Sam Meyer based on a simple adventure game engine by [Adam Smith](https://github.com/rndmcnlly).

Code requirements:
- **4+ scenes based on `AdventureScene`**: CForest, Lake, Tower, Wizard
- **2+ scenes *not* based on `AdventureScene`**: Intro, Outro
- **2+ methods or other enhancement added to the adventure game engine to simplify my scenes**:
    - Enhancement 1: Added shake which automates shaking animation
    - Enhancement 2: Added dissappear which automates an item dissappearing after being picked up

Experience requirements:
- **4+ locations in the game world**: Crystal Forest, Lake, Wizard Tower, Wizard's Room
- **2+ interactive objects in most scenes**: Go Back in almost all scenes, most also have an additional item such as a crystal
- **Many objects have `pointerover` messages**: Crystal : "Shiny yet deadly sharp", Go Back "You're done here"
- **Many objects have `pointerdown` effects**: Crystal: "Owch!", Crystal Ball: "Got the Crystal Ball"
- **Some objects are themselves animated**: Key flies down, Crystal shakes when trying to pick it up

Asset sources:
- (For each image/audio/video asset used, describe how it was created. What tool did you use to create it? Was it based on another work? If so, how did you change it, and where can we learn more about the original work for comparison? Use [Markdown link syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links).)

Code sources:
- `adventure.js` and `index.html` were created for this project [Adam Smith](https://github.com/rndmcnlly) and edited by me.
- `game.js` was sketched by [Adam Smith](https://github.com/rndmcnlly) and rewritten by me.