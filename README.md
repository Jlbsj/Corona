# Corona
import turtle
t1=turtle.getscreen()
t1.bgcolor("black")
s1=turtle.Turtle()
s1.pencolor("white")
s1.penup()
s1.goto(0,200)
s1.pendown()
a=0
b=0
s1.speed(0)
while True:
    s1.fd(a)
    s1.rt(b)
    a+=3
    b+=1
    if b==210:
        break
s1.ht()
turtle.exitonclick()
