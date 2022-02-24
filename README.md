# Calculator

This tutorial is about making arduino calculator. We will build two digit arduino calculator using arduino uno, 4×4 numeric keypad and 16×2 lcd. This particular arduino calculator can perform six functions addition, subtraction, multiplication, division, power and reminder. Code is easy to understand but its lengthy. If you are already familiar with the arduino coding syntax, you can easily understand the code below. If you are not than take some tutorials to become familiar with arduino language syntax. 


**Arduino calculator project requirements**


1)Arduino uno     (Microcontroller) \n
2)4×4 Keypad      (Taking input from Users)
3)16×2 Lcd        (Displays Result)
4)Potentiometer   (Setting Lcd Contrast)


Arduino uno is used as microcontroller in the project. Arduino takes the input from user and after analyzing the instructions produces output. The output is than displayed on 16×2 lcd. 4×4 numeric keypad is used as input. User presses the buttons on keypad to give input to arduino calculator. Arduino calculator takes two digits and an operator as input. Arduino calculator then identifies the operator, computes results according to the operator and then displays the result on 16×2 lcd screen.

Lcd 16×2 is interfaced in 4-bit mode with arduino uno. Arduino pins D13, D12, D11, D10, D9 and D8 are occupied by 16×2 lcd. 4×4 Keypad rows are connected to pins  D4, D5, D6 & D7 of arduino uno. Coulombs of keypad are connected to pins D0, D1, D2 & D3 of arduino uno. 
