# creating-art
use python turtle graphics, store data in lists and create a geometric shape
import turtle
shelly = turtle.Turtle()
# move shelly forward 100 steps
shelly.forward(100)
# turn shelly right 90 degrees
shelly.right(90)
# turn shelly left 60 degrees
shelly.left(60)
# moves shelly backward 100 steps
shelly.backward(100)
# makes shelly draw in red color
shelly.color('red')
# makes shelly draw a circle
shelly.circle(10)
# makes shelly lift pen
shelly.penup()
# makes shelly put the pen down to draw
shelly.pendown()
# clears screen and goes back to start position
shelly.reset()
# move to x coordinate 35, y coordinate 80
shelly.goto(35,80)
# makes shelly not visible on the screen
shelly.hideturtle()

#change turtle shape
shelly.shape('turtle')
# print coordinates-- find shelly
print(shelly.xcor(), shelly.ycor())
35 80

# loop
for i in range (4):
    shelly.forward(100)
    shelly.left(90)
    print(i)

0
1
2
3
for n in range(6):
    for i in range(4):
        shelly.forward(100)
        shelly.left(90)
    shelly.right(60)

# lists
colors = ['red', 'green', 'blue']
colors[0]
'red'
colors[1]
'green'
colors[2]
'blue'

#creating geometric art

for i in range(6):
    shelly.forward(100)
    shelly.left(60)

for n in range(36):
    for i in range(6):
        shelly.forward(100)
        shelly.left(60)
        shelly.right(10)
