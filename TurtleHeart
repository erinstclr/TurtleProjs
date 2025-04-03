import math
from turtle import *

def hearta(k):
    return 15 * math.sin(k) ** 3

def heartb(k):
    return 12 * math.cos(k) - 5 * math.cos(2 * k) - 2 * math.cos(3 * k) - math.cos(4 * k)

# Setup Turtle
speed(1000)  # Use 0 for the fastest speed
bgcolor("black")
penup()
goto(0, 0)
pendown()

# Draw the heart shape
for i in range(6000):
    k = i / 100  # Scaling factor to make it smooth
    x = hearta(k) * 20  # Scale up the shape
    y = heartb(k) * 20
    goto(x, y)
    color("red")
    dot(3)  # Make a small dot at each point

done()
