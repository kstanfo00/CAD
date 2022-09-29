# CircuitPython
This repository will actually serve as a aid to help you get started with your own template.  You should copy the raw form of this readme into your own, and use this template to write your own.  If you want to draw inspiration from other classmates, feel free to check [this directory of all students!](https://github.com/chssigma/Class_Accounts).
## Table of Contents
* [Table of Contents](#TableOfContents)
* [Hello_CircuitPython](#Hello_CircuitPython)
* [CircuitPython_Servo](#CircuitPython_Servo)
* [CircuitPython_LCD](#CircuitPython_LCD)
* [NextAssignmentGoesHere](#NextAssignment)
---

## Hello_CircuitPython

### Description & Code
This assignment was our intro assignment to circuitpython. Our job was to get the neopixel to blink and change colors. 



```python
import board
import neopixel
import time 

dot = neopixel.NeoPixel(board.NEOPIXEL, 1)
dot.brightness = 0.5 
while True:
    dot.fill((0, 0, 255))
    time.sleep(0.5)
    dot.fill((255, 255, 255))
    time.sleep(0.5)
```


### Evidence


![Untitled_ Sep 27, 2022 3_18 PM (1)](https://user-images.githubusercontent.com/112961430/193047596-eea5442e-cbe6-4e91-b174-e436803c214c.gif)




Image credit goes to [Kaz S](https://github.com/kshinoz98/CircuitPython#Hello_CircuitPython)


### Wiring
Make an account with your google ID at [tinkercad.com](https://www.tinkercad.com/learn/circuits), and use "TinkerCad Circuits to make a wiring diagram."  It's really easy!  
Then post an image here.   [here's a quick tutorial for all markdown code, like making links](https://guides.github.com/features/mastering-markdown/)

### Reflection
What went wrong / was challenging, how'd you figure it out, and what did you learn from that experience?  Your ultimate goal for the reflection is to pass on knowledge that will make this assignment better or easier for the next person.




## CircuitPython_Servo

### Description & Code

```python
Code goes here

```

### Evidence

Pictures / Gifs of your work should go here.  You need to communicate what your thing does.

### Wiring

### Reflection




## CircuitPython_LCD

### Description & Code

```python
Code goes here

```

### Evidence

Pictures / Gifs of your work should go here.  You need to communicate what your thing does.

### Wiring

### Reflection





## NextAssignment

### Description & Code

```python
Code goes here

```

### Evidence

### Wiring

### Reflection