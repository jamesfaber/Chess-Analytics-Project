# Chess API Project ♟

As an avid chess player, I’m always eager to explore new strategies and refine my skills. One day, while playing on the Chess.com app, I began to wonder if I could apply statistical analysis to my gameplay history. A quick Google search revealed that Chess.com offers a public API, and in that moment, inspiration struck. I decided to channel my curiosity into a project, diving into the data to (hopefully) uncover meaningful insights and patterns.

The first program I created was a search tool to collect and display game data for a single user. I developed this tool for two reasons: to determine if there were any high-level patterns in my gameplay history, and to become familiar with the API. One insight I discovered was that I generally had a higher level of success when I played the Sicilian Defense opening, however for one particular variation of that opening I lost almost all my games. Now I know to keep an eye out for that variation in the future.

The second program I created was a program that gathered random rapid-speed chess games from the API for players around my skill level.  I wanted to see if I could find some insights in this data to help improve my own game, so I engineered features that I thought might potentially explain wins. I focused on creating features based on the opening phase of the game, such as whether a player moved their queen in the first 12 moves. 

The final program that I created was an R program to test the significance of these features via analyzing Logistic Regression models. The final program with output and takeaways can be viewed by downloading the file "Chess-Game-Final-Analysis.html".
