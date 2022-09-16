# Guess The Number Game API

A Spring Boot, RESTful web API for a code-breaking game that replicates the traditional "Bulls & Cows".
Users must crack the 4 digit, hidden, and carefully generated code by making guesses until they guess correctly. After each guess(round), users
are given the number of exact and partial matches.
The game keeps track of all games and details of each round within a game including all exact/partial match feedback, guess times, and user guesses.

<ul>
<li>Makes use of a Service Layer for all game logic</li>
<li>MySql to store Game and round data</li>
<li>Spring JDBC Template for DB Connectivity</li>
<li>Both Daos tested thoroughly with Junit</li>
<li>Ready to serve a front-end client</li>
</ul>

Technologies used:

![Tech Stack](https://skills.thijs.gg/icons?i=java,spring,git,maven,mysql)