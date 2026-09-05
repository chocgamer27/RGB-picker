# RGB-picker
This is an RGB picker!

### This is inspired by something like this
<img width="502" height="251" alt="image" src="https://github.com/user-attachments/assets/874c1f2b-7227-4f34-934b-94493a00fdba" />

-- context (it was a group of bored developers who made a reddit post or thread to try and make the worst volume control)

### info on it and how it works
There are 43 coloured boxes for each colour (43 for red, 43 for green, 43 for blue)
The reason its 43 and not 44 or 42 or anything else is because 42.5*6 = 255 (rgb values max at 255), and I cant have half a box so how it works is if the total value is 255 or bigger then 255 then it just equals 255.
When you click on roll it randomises every single box's value (if it rolls above 6 then it keeps rolling till is 6 or below), if the box is disabled (shown by opacity and in code shown by btn.locked -- btn being the subject button / coloured box and .locked being a boolean value (only able to be true or false).
The total of all the certain colour's boxes values is shown at the top by adding up all the vaules (including locked/disabled box's values).
on the bottom right there is a piece text showing the background as the rolled rgb value R being the total from Red column, G for green column, etc.
The colour of the text is based off of the background colour so if the background colour is quite dark then the text is white and if the background is bright then the text is dark.
If you click on the (button) that shows the rgb value it will copy "rgb(R, G, B)" R,G,B being their respective column values.

How you'd get the values you'd want is say you want a low red-ish colour,
you'd roll and lock all the red ones you want to be a low number like 0 or 1 
or if you'd want a quite a red-ish colour you'd lock them at a high number like 5 or 6
and just do that for all the colour columns and you can see the rgb colour at the "rgb(R, G, B,)" text thing's background

## CREDITS (Stuff I didnt make/Hard mode)
### Hard mode was made by math0171512,

math0171512 suggested it in a discord server I shared the project with.
math0171512 Contributed to the project by adding in hard mode 
#### Hard mode
Hard mode still lets you use it as normal in the aspect of rolling and seeing the colour as the background of the gui aspect that usually shows "rgb(R, G, B) and lets you copy the text. But hardmode stops you from copying the text from that button or from seeing the text on it that usually says "rgb(R, G, B)"

math0171512 also suggested hardmode then was just like nah I'll just Fork the project then request commit to it (I think thats what its called??).
Credit to math0171512
Also visit math0171512 ⬇️⬇️

https://github.com/math0171512
