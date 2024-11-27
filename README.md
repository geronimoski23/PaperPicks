# PaperPicks
Paper Picks, allows users to track and analyze their prop bets while also sharing and receiving input on their analysis. This project combines a notion database with the Framer's web builder along with React, Typescript, and JavaScript to create a platform where sports bettors can connect. 

### Data Entry and Database Creation
The first part of my prototyping journey was creating and populating databases that my website would need to use. In order to populate my database, I used the Glitch IDE to read data from the Prize Picks API and access the data in real time so that my database contained up to date information regarding possible bets that could be placed. In then used notion's relational database properties to connect a total users database, user info database, and a player cards database.

### Front End Creation
The second portion of my prototyping journey was to create a card component that would display the data from my notion database into individual cards on framer. I did this by taking a screenshot of the type of card I wanted to design from https://www.prizepicks.com. After finalizing what needed to be displayed on the card, my final card dedsign looked like this and held 8 components:



1. Player Image
2. Player Name
3. Team Name
4. Player Position
5. Opponent Team
6. Game Time
7. Stat Line
8. Stat Category

