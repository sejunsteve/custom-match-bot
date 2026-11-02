\# custom-match-bot



Discord custom match helper



\## Project Goal



When having custom matches with friends, players need to manually divide players into teams, select a map, move players into separate voice channels, record teammates and results, etc. This projects is made to automate organization of custom match from start to end, using Discord bot.



\## How it works



1. Players interact with Discord (as a form of slash command or other interactions) to start match.
2. Bot collects players from voice channel and randomly divides them into two teams.
3. Bot randomly selects a map from the list.
4. Bot creates team voice channels and move players into their assigned channels.
5. Bot sends the message about team assignments and selected map.



More in depth:



!\[System Architecture Diagram](docs/System-Architecture-Diagram.png)



\## MVP Scope



* Register players from voice channel
* Randomly divide players into two teams
* Randomly select a map from the list
* Create team voice channels and move players
* Display team assignments and the selected map



MVP will focus on supporting one game and one match at a time.



\## Future Roadmap



\- \[ ] Random captain selection and player selection for captain

\- \[ ] Map banning before selection

\- \[ ] Support multiple games using Game class/interface

\- \[ ] Match history and stats saving

\- \[ ] Multiple match at the same time


More on \[Eisenhower Matrix](docs/Eisenhower-Matrix.pdf).



\## Tech stack



* Language: `TypeScript` w/ `Node.js`
* Libraries: `discord.js`, `@sapphire/framework`
* Data Storage: `JSON`
* External API: Discord API



\## Documentation



You can find project documentations in `docs/` folder, including:



* \[Eisenhower Matrix](docs/Eisenhower-Matrix.pdf)
* \[Visio - System Architecture Diagram](docs/System-Architecture-Diagram.vsdx)
* \[Image - System Architecture Diagram](docs/System-Architecture-Diagram.png)



