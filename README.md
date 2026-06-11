# BallSpawnerPracticeProject

This is a simple beginner Unity project that uses object oriented programming to spawn different types of balls at timed intervals, demonstrating inheritance, method overriding, and basic gameplay logic.



The project features a base Ball class that controls shared movement behaviour, with child classes like GreenBall and RedBall modifying or extending that behaviour. A BallSpawner script is used to create different ball types in the scene at regular time intervals using a timer system. Each time the timer finishes, a random ball prefab is selected and spawned into the scene using Unity’s Instantiate method. The balls behave differently depending on their class, showing how derived classes can change or override base functionality. This project also makes use of Unity components such as Rigidbody2D, prefabs, and the update loop to create continuous gameplay behaviour.

