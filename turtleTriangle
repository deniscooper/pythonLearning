import turtle

triangleLength = 300
triangleAngle = 120
squareLength = 300
squareAngle = 90
squareColor = 'red'
triangleColor = 'green'
bgColor = 'blue'



turtle.bgcolor(bgColor)

#build a yellow triangle
turtle.penup()
turtle.goto(-150,100)
turtle.fillcolor(triangleColor)
turtle.begin_fill()
turtle.pendown()

for i in range(3):
    turtle.forward(triangleLength)
    turtle.left(triangleAngle)

turtle.end_fill()

#build a square
turtle.penup()
turtle.fillcolor(squareColor)
turtle.begin_fill()
turtle.pendown()

turtle.left(270)
for x in range(4):
    turtle.forward(squareLength)
    turtle.left(squareAngle)

turtle.end_fill()

turtle.exitonclick()