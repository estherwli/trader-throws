![alt text](https://i.imgur.com/5XACEWr.png "Logo")
![alt text](https://i.imgur.com/WP7WBho.png "Concept Art")


## Setting up
* Windows: run Host.command as administrator, then open localhost:8000 in Google Chrome
* MacOS: right click and open Host.bat (may need to set file permissions to 744), then open localhost:8000 in Google Chrome

## Story
This game takes place in a small grocery store, and you’re the employee on the first shift. Your responsibility before the store opens each day is to sort and restock all the merchandise. After sleeping through your alarm and getting to work extremely late one morning, you find that you only have a minute to organize everything before your boss arrives. The items can be sorted into 3 categories: food, home & office, and trash. In an ambitious attempt to not get fired, you must quickly throw everything together… no pun intended!

## Controls
* s - start/restart
* a - turn left
* d - turn right
* t - throw projectile
* 5 - default view (while in this view, mouse picking is enabled for computers with screen resolution 2880 x 1800)
* 0 - start/change background music
* c - challenge mode
* n - normal mode

## Objective
* each projectile that lands in the correct bin earns 1 point in normal mode, 2 points in challenge mode
* each round begins with 5 lives; every unsuccessful throw deducts a life
* complete as many correct throws as possible in given time

## Advanced Features
1. Physics-based animation:
    * projectile trajectory
    * mid-air angular motion based on projectile's moment of inertia
    * rebound calculation when projectile hits front or rim of bin
    * collision detection using rectangular bounding boxes
2. Mouse picking: click on green cashier sign or lucky cat to zoom in for details
![alt text](https://i.imgur.com/1Cfhmpm.gif "Mouse picking")
3. Bump mapping: floor tiles contain slightly perturbed normals 
4. Sprite animation: scrolling texture cashier monitor
5. Shadow mapping: light brown shadows according to a single central light source

## Design Process 
![alt text](https://i.imgur.com/nRjLBDF.png "Design process 1")
![alt text](https://i.imgur.com/d8OZdOm.png "Design process 2")

