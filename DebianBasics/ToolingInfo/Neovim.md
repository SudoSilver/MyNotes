Neovim is a fork of vim so essentially it is a rework of vim and a great text editor. While it may be hard to learn here I have some basics. 

--- 
Modes: 
-> esc takes you from any mode to normal mode
-> v takes you from normal mode to visual mode
-> a takes you from normal mode to insert mode 

Normal mode is where you typically go just to move to another mode or move with the h j k l keys.

Visual mode is where you go to select words.

Insert mode is where you type.

---
Moving:
In Neovim one of the perks is that you can move with the h j k l keys which once you get used to is much faster but of course you can also move with the arrow keys.

To move using h j k l you first need to enter normal mode then
-> h for left
-> j for down 
-> k for up
-> l for right

You can also use
-> w to move to the beginning of the next word
-> e moves to the end of the current word press it again to go to the end of the next word

---
Copy/Cut/Paste:
First enter visual mode to press v (you need to be in normal mode to do that) then move around in any way you like and use:

-> y to copy
-> x to cut
-> p to paste

The clipboard is a bit complex and I don't feel comfortable with explaining it as I just took some config files from GitHub for that which is perfectly fine to do I encourage you to do take config files from others. For copying to clipboard go check for YouTube tutorials there are many great vim or Neovim tutorials and they are very similar.

---
Quitting Neovim: 
First enter normal mode then type
-> :w to write without quitting so basically the same as ctrl + s everywhere else
-> :q to quit without saving
-> :wq to write and save