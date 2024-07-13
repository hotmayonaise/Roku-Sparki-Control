# Roku-Sparki-Control
Lets you control a Sparki robot with a Roku remote 
----------------------

Basically this gives you all the codes for making a roku remote interact with the Sparki robot. This uses the Sparkiduino IR library.

ex. 
```
  int OK = 170
  
  if (irCode == OK){
    sparki.RGB(RGB_GREEN);
  }
```

### OK button
The 'OK' Button is integer 170 

Here is code that turns the RGB light green when you press the 'OK' button 

```
  int OK = 170
  
  if (irCode == OK){
    sparki.RGB(RGB_GREEN);
  }
```

### Down Arrow
The '↓' Button is integer 51

Here is code that turns the RGB light green when you press the '↓' button 

```
  int DOWN = 51
  
  if (irCode == DOWN){
    sparki.RGB(RGB_GREEN);
  }
```
