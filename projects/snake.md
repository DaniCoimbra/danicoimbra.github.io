---
layout: project
type: project
published: true
image:  img/snake.png
title: "Snake Game"
date: 2022
labels:
  - C#
  - OOP
  - MVC
  - Network
summary: The Snake Game is a client/server software program, the project aims to create a multiplayer snake game, with obstacles, power up, and enemies. Players can connect using TCP/IP protocols, using networksockets for remote communication.

---
<br>
<br>

<img class="img-fluid" src="../img/snakeGIF.gif" style="width: 75%; display: block; margin: 0 auto;">

<br>
<br>

<div class="project-summary">
  <h1>Snake Game</h1>
  <p>
    The classic Snake Game, reimagined with multiplayer capabilities, AI enemies, and power-ups.
  </p>
</div>

<h2>Overview</h2>
<p>
  The Snake Game project is a multiplayer client/server application developed in C#, designed to enhance the traditional Snake gameplay with added challenges and features. Players can connect via TCP/IP protocols using network sockets, making the game accessible across remote connections. The game also included obstacles, power-ups, and AI-controlled enemies, adding layers of strategy and excitement.
</p>

<h2>Architecture</h2>
<p>
  The project follows the Model-View-Controller (MVC) pattern for a clean and maintainable codebase. The Model manages game data, the View handles rendering and user input, and the Controller processes network information and updates the game state. JSON is used for efficient data transfer between the server and client, ensuring smooth synchronization and accurate game rendering.
</p>

<h2>Features</h2>
<ul>
  <li>Multiplayer functionality with client/server architecture.</li>
  <li>Enhanced gameplay with obstacles, power-ups, and AI enemies.</li>
  <li>Efficient network communication using TCP/IP and JSON.</li>
  <li>Structured MVC pattern for maintainable and scalable code.</li>
</ul>
 
Source: <a href="https://github.com/DaniCoimbra/SnakeGame">Snake Game</a>
