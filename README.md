![alt text](https://github.com/intro-graphics-master-F19/term-project-team-costcode/blob/master/assets/traderthrows.png "Logo")
![alt text](https://github.com/intro-graphics-master-F19/term-project-team-costcode/blob/master/assets/trader-throws-concept-art.png "Concept Art")


### Abigail Yang
 * 604970275
 * ayang99@ucla.edu
 * @yangjabigail
 
### Esther Li
 * 604892225
 * esther.li@ucla.edu
 * @estherwli
 
### Jihye Kim
 * 605181667
 * lklk875@gmail.com
 * @lklk875
 
### Therese Cook
 * 205015868
 * tmcook@ucla.edu
 * @sarumanplaysguitar

## Story
This game takes place in a small grocery store, and you’re the employee on the first shift. Your responsibility before the store opens each day is to sort and restock all the merchandise. After sleeping through your alarm and getting to work extremely late one morning, you find that you only have a minute to organize everything before your boss arrives. The items can be sorted into 3 categories: food, home & office, and trash. In an ambitious attempt to not get fired, you must quickly throw everything together… no pun intended!

## Specifics
We will make an item-tossing game similar to a basketball-throwing game, where the user tries to score points by aiming and throwing projectiles into bins. However, instead of basketballs, we will create objects to resemble grocery items and create different bins to correspond to different categories of items (such as types of produce, stationery, packaged goods, etc.) to resemble what typical inventory the employee would encounter. We will make the viewer’s objective to sort through randomly generated items and to toss them into the correct bin. A camera will be positioned to view the projectile object, pointing in the direction of the bins. After throwing one object, a new one will be generated and will appear on the screen. We hope to implement a point system that rewards points for every correct throw and display the score on the screen. The game will have a time limit, and the user’s objective will be to complete as many correctly-aimed throws as possible.

## Application of Course Material
We plan to use procedural animation, specifically physics-based animation, to simulate the projectiles being thrown and falling through the air. In addition, we will use the steps learned in class to use indexed face sets and triangulation to generate various shapes, including spheres, cubes, cylinders, and other 3D figures. We will also use texture rendering, shading, and various types of lighting to differentiate different surfaces and objects, creating a more realistic scene. Lastly, we will utilize matrix operations to shift camera view as the animation continues. 

## Interactivity
To add interactivity to our project, we will implement user controls that will allow the user to choose when to throw the object, such as pressing a key to throw. We will also allow the user to move around in the scene, so we will need to add controls to move the camera (eye) location, such as using the four arrow keys to look around the scene.

## Advanced concepts
Advanced features we hope to implement include multiple target bins instead of one target bin, and a detection for which bin the item was thrown into, with a point deduction if an object is thrown into an incorrect bin.

We will implement collision detection and reaction to collision (if the object hits the left vs. right side of the bin). We will also use advanced physics concepts like 2-dimensional projectile motion simulation and corresponding rebound angle calculations. Our goal is to produce shadows for every bin, and if time permits, a moving shadow for the ball as well.



