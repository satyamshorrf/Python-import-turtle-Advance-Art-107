# Python-import-turtle-Advance-Art-107
Create python use import turtle graphics code
from turtle import*
from time import*
import colorsys
title("Satyam Shorrf")
bgcolor("black")
tracer(20)
sleep(2)
def draw():
    h=0
    for i in range(100):
        c = colorsys.hsv_to_rgb(h,1,1)
        h += 0.9
        up()
        goto(0, 0)
        down()
        fillcolor(c)
        begin_fill()
        right(98)
        circle(i, 10)
        forward(90) 
        forward(i) 
        left(20)
        for j in range(129):
            forward(i) 
            circle(i, 285, steps=2) 
        end_fill() 
draw() 
done() 
 
