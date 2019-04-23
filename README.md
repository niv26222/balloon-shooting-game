# balloon-shooting-game
Balloon Shooting Game is a simple game using c and cpp features



Balloon Shooting Game is a simple game using c and cpp features. You can easily learn and is easy to run because this game works in TURBOC compiler.
The main features are included is GRAPHICS and DOS commands.

Basic commands used in this game :
initgraph : initgraph is used to initialising of graphics mode in the program.
                 ex. initgraph(&gm,&gd,"akshay");
here gm uses Graphics detect mode and gd points to graphics features to be used in program ans last is a string it may be any string like c://tc/bin etc..
setbkcolor : sets the current background color.
   for ex. if you want to set background color to blue, you can call setbkcolor(BLUE); or setbkcolor(1);
getimage : saves a bit image of the specified region into memory.
putimage : outputs a bit image onto the screen.
settextstyle : sets the current text characteristics.
   Declaration : settextstyle(int font, int direction, int charsize);
outtextxy : displays a string at the specified location (in graphics mode).
   Declaration : outtextxy(int x, int y, "textstring" );
itoa : converts an integer to a string. It lies on stdlib header library.
   Return Values : On success, point to target string. On error, there is no error.
