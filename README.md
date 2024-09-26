# f24-lab05

- Task 1

public boolean isOccupied(int position)

Feature envy: Road holds the information but Frogger excutes all the getter resposibilites

- Task 2

Long parameter list: a long list of parameters provided to a method.

- Task 3

The "draw" function seems to duplicate itself. 
How would you refactor it so that we don't need to rewrite the functionality everytime we introduce a new file type?

delegation

Take a look at Drawing.java. Somewhere inside the "draw" function, the code seems to be explicitly creating an array of Lines and feeding it to the shape. 
How would you refactor it so that we don't need to expose and rely on such information inside our Drawing class?

shape.draw()
information expert