# IN204
This repository will contain my project for IN204.


The background :
    a scrolling image that shows movement (dotted lines and trees on the side of the road show the movement)

    it correspond to tha accessible area for the cars :
    with the edges of the bridge being known by two limit x-axis values

    The width of the road does not vary
    Road shapes : | | , ||,  /| , \| , |\ , |/
        (2 lanes & 3 lane strait roads)
    


The static objects :
    Obstacles :
        They appear as other cars, rocks, or holes.
        They create a collision with the car.
    Items :
        Hearts and coins.
        They do not create a collision and disappear when grabbed by a driver.

The cars :
    There are two players at the same time on the playground.
    When they touch, they bump on each other.
    (a strategy for winning would be to push your opponent off the bridge)

    At every iteration of the game loop, the position of the car is checked :
        being off the bridge = loosing
        crashing into an obstacle = loosing a life
    
 
