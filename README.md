Airport Challenge
=================

```
        ______
        _\____\___
=  = ==(____MA____)
          \_____\___________________,-~~~~~~~`-.._
          /     o o o o o o o o o o o o o o o o  |\_
          `~-.__       __..----..__                  )
                `---~~\___________/------------`````
                =  ===(_________)

```

Description
-----
This program was built in week 1 of Makers Academy to create an airport program (described in detail below).

Approach
----
I first built a pen-and-ink colour diagram of the classes and methods required as derived from the user story.

I then began to build feature and unit tests, starting with the ```Plane``` class and also creating ```Weather``` and ```Airport``` classes.

Most of the methods were held in the ```Airport``` class.  Edge cases still to be defended against include:
1. Planes can only take off from airports they are in
2. Planes already flying can't take off
3. Planes flying can't be in the airport
4. Landed planes can't land again

Requirements
-------
Ruby
bundle
rspec

Task
-----

We have a request from a client to write the software to control the flow of planes at an airport. The planes can land and take off provided that the weather is sunny. Occasionally it may be stormy, in which case no planes can land or take off.  Here are the user stories that we worked out in collaboration with the client:

```
As an air traffic controller 
So I can get passengers to a destination 
I want to instruct a plane to land at an airport and confirm that it has landed 

As an air traffic controller 
So I can get passengers on the way to their destination 
I want to instruct a plane to take off from an airport and confirm that it is no longer in the airport

As an air traffic controller 
To ensure safety 
I want to prevent takeoff when weather is stormy 

As an air traffic controller 
To ensure safety 
I want to prevent landing when weather is stormy 

As an air traffic controller 
To ensure safety 
I want to prevent landing when the airport is full 

As the system designer
So that the software can be used for many different airports
I would like a default airport capacity that can be overridden as appropriate
```



