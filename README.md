# Pythons-Love-Turtle
Developed By APM MODZ "AJALJERRY"



## _[Youtube Support](https://youtube.com/c/APMMODZ)_


## _[Follow On Instagram](https://instagram.com/Ajuzz_pc)_
  
  
## _[Follow On Whatsapp Group](https://chat.whatsapp.com/IBK2I44EHgHFPuTsv5K40I)_






















____________________________________________________________________________CODE_____________________________________________________________________________



___program__


Make a Heart and print 'I LOVE YOU' using Python Turtle
Coding with AnimationMarch 23, 2022Course2 Comments
Make a Heart and print 'I LOVE YOU' using Python Turtle 




Watch here

Source code :

import turtle 

from turtle import *



wn = Screen()

wn.bgcolor('black')



t = turtle. Turtle()

t.pencolor('white')



def curve():

       for i in range (200):

             t.rt(1)

             t.fd(1)

       

def heart():

       t.fillcolor('red')

       t.begin_fill()

       t.lt (140)

       t.fd (113)

       curve () 

       t.lt (120)

       curve() 

       t.fd(112)

       t.end_fill()



heart()

t.ht()



def write(message,pos):

       x,y=pos

       t.penup()

       t.goto(x,y)

       t.color('white')

       style=("Stencil Std", 18, "italic")

       t.write(message, font=style)



write('I',(-68,95))

write('L',(-55,95))

write('0',(-42,95))

write('V',(-30,95))

write('E',(-14,95))

write('Y', (10,95))

write('0', (26,95))

write('U', (45,95))



wn.mainloop()




