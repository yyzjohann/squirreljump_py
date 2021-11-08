# squirreljump_py: A squirrel jump game in python

In a forest there lives a squirrel, and it likes to jump between the treetops there. It can jump at most two treetops away, and only to a treetop which is strictly lower than the one it stands on. It can always jump to the trunk of an adjacent tree and climb up, or climb up from the bottom of the forest, so it does not matter where the squirrel starts. We want to know the maximum number of jumps it can make in a given forest.

The forest is given by a list of integers (the heights of the trees), so for example the forest 

#
# #
# # #
# # # # #   
# # # # # # #
# # # # # # # #

is given by the list [6,5,4,3,3,2,2,1]. 

To run the program simply do 

> python3.X SquirrelJump.py

In the same file (SquirrelJump.py) you can choose (by commenting in/out) between different forests; this program does not have an IO functionality.

There are also some tests included, to run them do

> python3.X -m unittest Test.py
