# IMGD5010-w1_byob_Xingyi-Liu
Assignment 1

## Instructions for B-Canvas:
Start with Palette state, color is null.

Draw on a 14*14 cell canvas, use the line break command to go to next line from the top. Return to the first line when you at the last line.

Switch: Palette/ Brush
Use the switch command to enter the palette state or brush state. In palette state you can select a color. After selecting, it will do nothing to the canvas until you use the filling command to fill the entire line, or switch to the brush state to draw.

In the brush state, coloring the cell which specified by command.


## Command List:
### Color list:
0000 - red

0001 - orange

0010 - yellow

0011 - light green

0100 - green

0101 - cyan

0110 - blue

0111 - purple

1000 - magenta

1001 - pink

1010 - gray 

1011 - black

1100 - white 

1101 - null 
(transparent/use it as eraser)

1110 - fill line

1111 - switch

![palette list](https://github.com/user-attachments/assets/2bdd5834-0207-4f8d-b1fd-ecc62c62fdf0)

### Brush list:
0000 - coloring cell 1

0001 - coloring cell 2

0010 - coloring cell 3

0011 - coloring cell 4

0100 - coloring cell 5

0101 - coloring cell 6

0110 - coloring cell 7

0111 - coloring cell 8

1000 - coloring cell 9

1001 - coloring cell 10

1010 - coloring cell 11

1011 - coloring cell 12

1100 - coloring cell 13

1101 - coloring cell 14

1110 - next line

1111 - switch

![brush list](https://github.com/user-attachments/assets/f52af3fe-ba32-4261-825b-ae16c52a42d9)




## Example
### Heart
![heart](https://github.com/user-attachments/assets/e4353a76-1c42-42e6-a182-c78e65fd1b1d)

1001 1111 0010 0011 0100 1001 1010 1011 1110

1111 1110 1101 1111 0000 0110 0111 1101 1110

1111 1001 1110 1111 1110

1111 1110 1111 1110

1111 1110 1111 1110

1111 1110 1111 1110

1111 1110 1111 1110

1111 1110 1111 1110

1111 1110 1101 1111 0000 1101 1110

1111 1001 1110 1101 1111 0000 0001 1100 1101 1110

1111 1001 1110 1101 1111 0000 0001 0010 1011 1100 1101 1110

1111 1001 1111 0100 0101 0110 0111 1000 1001 1110

0101 0110 0111 1000 1110

0110 0111

![heart with cell](https://github.com/user-attachments/assets/eef37a7b-0a18-4ed4-82ad-d4c6938bedc7)


### Palette Rainbow:
![palette](https://github.com/user-attachments/assets/5dd62788-40fe-4800-b129-9c6816e398d1)

1100 1111 1110

1111 1110 1011 1111 1110

1111 1110 1010 1111 1110

1111 1110 1001 1111 1110

1111 1110 1000 1111 1110

1111 1110 0111 1111 1110

1111 1110 0110 1111 1110

1111 1110 0101 1111 1110

1111 1110 0100 1111 1110

1111 1110 0011 1111 1110

1111 1110 0010 1111 1110

1111 1110 0001 1111 1110

1111 1110 0000 1111 1110

1111 1110

![palette with cell](https://github.com/user-attachments/assets/aa4f6b96-f16a-41e2-8759-2e4884041f6b)


## Challenge
Try to draw a smiley face.

(In your own style, so you don't have to follow the image exactly)

![smile](https://github.com/user-attachments/assets/600dc333-8660-49d3-b8d8-d8d4c39b20f2)
![smile with cell](https://github.com/user-attachments/assets/7e6a1c08-eadf-4b4b-a0bd-a202e722eaf0)
