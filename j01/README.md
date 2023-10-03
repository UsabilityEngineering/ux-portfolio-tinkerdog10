**"Undoing Render Changes”**

**Sarah Youngdahl**

**9/22/2023**

I am currently working on a Computer Animation and Game Development major in the Animation Track with a CGI focus. In less confusing terms, this means I am learning how to make the visuals for a videogame or film. Much like a potter must sculpt a bowl and then paint on its color, I must create a blank 3D model and then add on color and details. For the task of adding color and details, I use a program called Adobe Substance 3D Painter. Think of it like Photoshop on a 3D canvas. 

After I finish with this task, also referred to as texturing, some of my classes require me to create a “render”. A render essentially means setting up the model with lighting and filters to make a high-quality photograph of my model in some sort of scene. One way to do this is to use a feature in the Substance Painter program called IRAY. Clicking the IRAY button opens a separate program window that allows me to adjust lighting and add filters that can help fake depth. I can also adjust the background as well as some photograph effects like the image’s overall contrast or saturation. It is a **useful** product that **serves the purpose** of allowing me to create a quick render without having to load my model and the texture into a separate program.

 ![Display settings in IRAY](/assets/J1_P1.png)
 
Unfortunately, the first time I used this feature revealed it to not be very **efficient** or **error tolerant**. My first assignment required me to create a texture for a provided “Spider Bot”.  The texturing portion of the assignment went smoothly. However, this was one of my assignments that required me to use the IRAY feature to create an image. This was my first time using the feature but we had a tutorial so I had some instructions to follow for how the different sliders and value inputs worked. 

Unfortunately, as I was adjusting some sliders, I realized I didn’t like the results of one of my adjustments. I wanted to undo my actions, so I used the common *mapping* for undoing an action in a computer program. On my keyboard I pressed “Ctrl” and then “Z”. Nothing happened. I tried it again. Nothing. I recalled that Photoshop uses a modified undo key press. I attempted to press “Ctrl” then “alt” and then “Z”. Still nothing. It was at this moment that I realized that the IRAY feature has no “undo” function. While it is easy to push a slider or setting too far the program provides no efficient way for the user to *recover from their mistake*. I had to undo my mistakes manually, tweaking the adjustment back and forth until I got close to where it was before. 

For instance, let’s say I decided to do some color corrections. I wanted to adjust the saturation, of my image. I would move the slider for saturation up. 

 ![Circled slider for saturation](/assets/J1_P2.png)
 
Unfortunately, that looks a little bright. So, maybe I could turn down the brightness to offset it?

 ![Result of saturation adjustment with brightness circled](/assets/J1_P3.png)
 
 ![Result of brightness adjustment](/assets/J1_P4.png)
 
Well, that did offset it, but now things are a little too dark in the scene. At this point, it would be better to start over again and make different adjustments. Unfortunately, there are only two options to achieve this. Firstly I would have had to have copied down the settings beforehand so I could past them back into the slider space, or to tweak down the sliders until I got close to the original result. 

![Attempt to reset image, with sliders and number inputs circled](/assets/J1_P5.png)

This method of image adjusting requires unnecessary extra effort on the user’s behalf. They are expected to remember the exact value that a setting had in the beginning before it was adjusted. For me, this was next to impossible, as I have a very bad memory when it comes to numbers. I was still able to produce some effective images, but it took more time than it needed to.  

![Final Render of image](/assets/J1_P6.jpg)

When it comes to computer programs like Substance Painter users like me come in with a **mental model** of certain functions a program should have and support. What makes the disconnect between my **mental model** and the **conceptual model** of how the program works all the more frustrating is the fact that the Substance Painter program normally supports the “ctrl + Z” method. The IRAY window is one of, if not the only feature in Substance Painter that doesn’t allow a user to undo their mistakes. This means that the user is suddenly expected to switch to an entirely different conceptual model for error prevention within the same program. My suggestion would be to reconcile this disconnect by having a way to undo mistakes throughout all features of the Substance Painter program, rather than just some of them. This would give the program better error tolerance and make the process more efficient. 
