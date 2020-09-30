# Snake-Game
If yoy want to create a snake game using Python then you should first install pygame. 
Basically pygame is important for every project in which you have created a game. Pygame installed 
by using command "pip install pygame".
After installing create a window using function "pygame.display.set_mode((x,y))" here, x and y are
the x distance in pixel and y distance in pixel. Game is created in this perticular window.
Now create a snake using  draw.rect() function, basically it is a rectangular shape and later on 
we made a function to increase the size of sanke by eating food.
We add four keys to give direction to snake like "pygame.K_LEFT" for left direction, "pygame.K_RIGHT"
for right direction, "pygame.K_UP" for upward direction and "pygame.K_DOWN" and for downward direction.
For adding score and length of snake we made a counter like C=0 at initial and give some condition 
if(food is eat) than C=C+1 and then score also increase by 1 and length also.

So this is the basic idea of snake game in python. Hope you understand this and I hope most of you 
build this game soon.
Happy learning........
