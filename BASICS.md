## Part 1: Basic movement, h, j, k, l, w, b
### press j to go down

### press l to follow the line
---------------------------o " press x to delete the o
                             " press j to go to the next action




### press l and j to follow the line and x to delete the o
-+
 |
 |                          
 +------+
        |
        |                          
        +------+
               |
               |                          
               +------o

### press l and j and h to follow the line and x to delete the o
-+
 |
 |                          
 +------+
        |
        |                          
 +------+
 |
 +------+
        |
        |                          
 o------+

### press l, j, h, and k to follow the line and x to delete the o
-+      +------+      +------+      +-----o
 |      |      |      |      |      |
 |      |      |      |      |      |
 +------+      |      |      +------+
               |      |
        +------+      |
        |             |  
        |             |
        |             |
        +-------------+

### press w to get to o and press x to delete
+-+      +------+      +------+      +-----o

### b = inverse w: press w, j, and b to get to o and press x to delete
+-+      +------+      +------+      +-----+
                                           |
o-+      +------+      +------+      +-----+

## Part 2: Basic Editing
### Delete a line with dd
delete me
delete me
delete me
delete me

### Yank and paste.  yy to yank line, p to paste line below, P above
yank me and paste below (yyp)
yank me and paste above (yyP)

### Visual Mode
#### Visual Mode
Highlight part of this line by pressing v, then navigate around 
escape to leave visual mode

#### Visual Line Mode
Highlight this line by pressing V, then navigate around 
escape to leave visual mode

#### Visual Mode + y / p
Highlight this line by pressing V, then press y  (What happened?)
press p (What happened?)

Highlight this point by pressing v, press wy  (What happened?)
press p (What happened?)

Lets repeat but with d instead of y, (What happened?)

## Part 3: The relationship of y / d
:h reg
:reg

What did we see there?

yank this line

What happened to the registers?

## Part 4: Insert mode
There are a few ways to go into insert mode

i: left side of cursor
a: right side of cursor
I: first character of line
A: last character of line
o: insert new line below line and go into insert mode
O: insert new line above line and go into insert mode

lets play around
