# dice
繰り返しされたし。
from vpython import*
import random
a=random.randint(1,6)
b=random.randint(1,6)
c=random.randint(1,6 )
if a==1:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(0,0,0),axis=vector(0,0,1),radius=1,color=color.red)
elif a==2:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),color=color.black) 

    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),color=color.black)
    
elif a==3:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(0,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)    
elif a==4:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)  
    
elif a==5:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(0,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)

    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)

    cylinder(pos=vector(-2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)    
else:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(2.5,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)    
    
    
#bに対応するサイコロ
if b==1:
    box(pos=vector(0-11,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(0-11,0,0),axis=vector(0,0,1),radius=1,color=color.red)
elif b==2:
    box(pos=vector(0-11,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(2.5-11,2.5,0),axis=vector(0,0,1),color=color.black)

    cylinder(pos=vector(-2.5-11,-2.5,0),axis=vector(0,0,1),color=color.black)
    
elif b==3:
    box(pos=vector(0-11,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(0-11,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5-11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5-11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)   
elif b==4:
    box(pos=vector(0-11,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(2.5-11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5-11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5-11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5-11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black) 
    
elif b==5:
    box(pos=vector(0-11,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(0-11,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5-11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5-11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)

    cylinder(pos=vector(-2.5-11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)

    cylinder(pos=vector(-2.5-11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)    
else:
    box(pos=vector(0-11,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(2.5-11,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5-11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5-11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5-11,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5-11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5-11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)    
        
if c==1:
    box(pos=vector(0+11,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(0+11,0,0),axis=vector(0,0,1),radius=1,color=color.red)
elif c==2:
    box(pos=vector(0+11,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(2.5+11,2.5,0),axis=vector(0,0,1),color=color.black)

    cylinder(pos=vector(-2.5+11,-2.5,0),axis=vector(0,0,1),color=color.black)
    
elif c==3:
    box(pos=vector(0+11,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(0+11,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5+11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5+11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)  
    
elif c==4:
    box(pos=vector(0+11,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(2.5+11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5+11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5+11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5+11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)  
    
elif b==5:
    box(pos=vector(0+11,0,0),length=10,width=1,height=10,color=color.white)

    cylinder(pos=vector(0+11,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5+11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5+11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)

    cylinder(pos=vector(-2.5+11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)

    cylinder(pos=vector(-2.5+11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)   
    
else:
    box(pos=vector(0+11,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(2.5+11,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5+11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5+11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5+11,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5+11,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5+11,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)      
