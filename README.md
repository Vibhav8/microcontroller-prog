for further information go to www.toptechboys.com
# microcontroller-prog

from visual import *
sphere1h=sphere(pos=(-1,0,0),radius=0.5,color=color.green)
box1h=box(pos=(-.5,0,0),length=.5,width=.5,height=.5,color=color.yellow)
cylindertar=cylinder(pos=(-.5,0,0),radius=.2,length=.7,color=color.red)
box2h=box(pos=(.5,0,0),length=.5,width=.5,height=.5,color=color.yellow)
sphere2h=sphere(pos=(1,0,0),radius=0.5,color=color.green)
box1v=box(pos=(0,0.5,0),length=.5,width=.5,height=.5,color=color.yellow)
box2v=box(pos=(0,-0.5,0),length=.5,width=.5,height=.5,color=color.yellow)
sphere1v=sphere(pos=(0,1,0),radius=0.5,color=color.green)
sphere2v=sphere(pos=(0,-1,0),radius=0.5,color=color.green)
while(1==1):

    for i in range(0,5):
        rate(5)
        sphere1h.radius=sphere1h.radius-.1
        sphere2h.radius=sphere2h.radius-.1
        sphere1v.radius=sphere1v.radius-.1
        sphere2v.radius=sphere2v.radius-.1
        box1h.length=box1h.length-.1
        box2h.length=box2h.length-.1
        box1v.length=box1v.length-.1
        box2v.length=box2v.length-.1
        cylindertar.pos=(cylindertar.x+.1,0,0)
        cylindertar.length=cylindertar.length-.1
        cylindertar.radius=cylindertar.radius-.025
    for i in range(0,5):
        rate(2)
        sphere1h.radius=sphere1h.radius+.1
        sphere2h.radius=sphere2h.radius+.1
        sphere1v.radius=sphere1v.radius+.1
        sphere2v.radius=sphere2v.radius+.1
        box1h.length=box1h.length+.1
        box2h.length=box2h.length+.1
        box1v.length=box1v.length+.1
        box2v.length=box2v.length+.1
        cylindertar.pos=(cylindertar.x-.1,0,0)
        
        cylindertar.length=cylindertar.length+.1
        cylindertar.radius=cylindertar.radius+.025
    
    
    
    
    
    
    
    
    
    


    






    






    
