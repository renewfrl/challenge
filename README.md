# Challenge

A Python OOP challenge. 

# Description

Imagine you want to model a radio (stereo). 

A radio can be either

- [ ] portable ghettoblaster 
- [ ] home stereo 

The radio have both three functions 

- increase volume. The volume level can be between 1-10
- turn on/off. This is a Boolean state
- sayHello. Prints the type of object to the ```console``` 

Only the portable ghetto blaster has the function battery power which returns  (random) value of 0-100 of the battery percentage. In case the percentage is < 5 => the ghetto blaster won't turn on 

# Solution

The solution consists of two objects. A fancy ghetto blasters and a good old stereo. 

Create those two objects using [Flask cli](https://flask.palletsprojects.com/en/2.0.x/cli/)


# Hints

- [ ] create a basic abstract class with ```ABC```  [link](https://docs.python.org/3/library/abc.html)
- [ ] Put the shared functions in this base class
