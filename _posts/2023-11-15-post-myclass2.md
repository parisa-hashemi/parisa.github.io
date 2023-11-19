---
layout: posts
title:کد درخت و فرکتال مثلث 
---


<html>
    <head>
        <title>tree</title>


    
         
        
            ابتدا تنه درخت را کشیده و در هر دفعه قطر قلم را اندازه شاخه را کم میکنیم
            
            سپس اگر شاخه ها از یک اندازه کم شد عمل شاخه تمام شده و برگ ها که دایره هستند کشیده میشوند
            
            

            from turtle import*
                import turtle
                
                
                def tree(d,r,s):
                    if d<10 or r<10 :
                     
                     dot(15,"green")
                
                     return
                    turtle.pensize(s)
                    turtle.pencolor("brown")
                    turtle.forward(d)       
                
                    turtle.left(r)
                    turtle.pencolor("green")
                
                    
                    tree(d * 0.75, r,s*0.7)
                    turtle.right(2*r)
                    turtle.pencolor("green")
                    tree(d *0.75,r, s*0.7)
                    
                
                    turtle.left(r)
                    turtle.backward(d)
                
                turtle.speed(0)
                turtle.left(90)
                
                
                
                    
                
                
                
                tree(100,30,15)
                
                turtle.mainloop()

            </pre>
            <br>


            برای  دیدن فرکتال مثلث

 <a href="file:///C:/Users/user/git/FC02031/s8/x.html"> اینجا</a>
 کلیک کنید 
 </div>     
    </body>
</html>