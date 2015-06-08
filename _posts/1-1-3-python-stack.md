---
layout: slide
title: trinket.io
lang: Python
data:
  background: "#69b3ef"
---

<section markdown="1">
trinket.io is there to teach code and python is a great first language!

{% include trinket-open type='python' %}
import turtle

tina = turtle.Turtle()

for c in ['red', 'green', 'yellow', 'blue']:
    tina.color(c)
    tina.forward(75)
    tina.left(90)

tina.penup()
tina.goto(-100,-50)
tina.write("Hello world!", font=("Arial", 30, "bold"))
{% include trinket-close %}

</section>
<section markdown="1">

And people get better and want more from trinket.

{% include trinket-open type='python' height='600' width='100%' %}
import numpy #can't forget this!
import matplotlib.pyplot as plt #our shortcut

x = numpy.linspace(0,5,20)      #create our first array
y = x**2    #this is how Python does exponents

plt.plot(x,y,'*')           #create the plot
plt.show()                  #show the plot
{% include trinket-close %}

What about performance?

</section>
