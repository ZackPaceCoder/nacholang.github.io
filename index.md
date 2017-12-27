# Nacho
Hello there! Welcome to the Nacho Language website! nice to see you.

you can download the source for nacho here, or you can go to github.com/JeremyPace/nacho

Code samples:

Comment:
```
#this is a comment!
```
make a simple application with this code:
```
#simple app
impl Nacho.gui;
impl Nacho.gui.button;
impl Nacho.gui.Label;

name("simple app")

public function(main) {
    new frame(frame1);
    new button(button1);
    new label(label1);
    
    #change the frame dimentions
    frame1.size(set(400, 300));
    
    #change the other component's dimentions
    button1.size(set(100, 60));
    label1.size(set(100, 60));
}


