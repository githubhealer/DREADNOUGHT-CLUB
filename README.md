# DREADNOUGHT-CLUB
import turtle

# Set up the turtle
t = turtle.Turtle()
t.speed(2)  # Set the drawing speed

# Draw the letter 'D'
t.penup()
t.goto(-100, 0)
t.pendown()
t.left(90)
t.forward(100)
t.right(90)
t.circle(-50, 180)

# Move to draw the letter 'N'
t.penup()
t.goto(-20, 0)
t.pendown()
t.left(90)
t.forward(100)
t.right(135)
t.forward(140)
t.left(135)
t.forward(100)

# Move to draw the letter 'T'
t.penup()
t.goto(0, 0)
t.pendown()
t.left(90)
t.forward(100)
t.penup()
t.goto(0, 50)
t.pendown()
t.right(90)
t.forward(80)

# Hide the turtle
t.hideturtle()

# Keep the window open
turtle.done()
