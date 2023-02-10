ABOUT ME

Hello! My name is Che-ann Wirjosentono and I am 15 years old. I'm from Santo Boma, Wanica.\
I am currently in VWO 4. I want to join the Inno-Starter because I want to become more experienced with computers, coding and making robotics.

![](https://lh6.googleusercontent.com/UJ7sGF9y7oD9eaQpmPWVzNho25bGEWkP7apa8c6DsKa38KZCGaVC6XiVU6WbAy2w5EArFyxGynuRTBaL4TEqTgERTlihr0_rCtZaceFTR7E_0voiAL8m3NYsnoVEusaNFiC2ZESiFbVpr6Qg4bqezuQ)\
--------------------

====================================================================================================================================================================================================================================================================================================================================================================================================================================================================================

Day 1 (5 september 2022)

Objective:\
Introduction to tinkercad\
Introduction to simple, serie and parallel circuits
========================================================================================================================

Introduction to the basic components

Built a basic blinking.

#### Component List :  Arduino uno R3  9V battery

Resistors  1.5V battery

Breadboard  Multimeters

LEDs  Diode

Pushbutton

HandsOn (Circuits Physical ) (screenshots):\
First we learned to make a simple circuit. You do that by connecting a LED with a battery.

For a LED not to burst there needs to be a resistor in the circuit.\
A resistor is an electrical component that limits or regulates the flow of electrical current in an electronic circuit.

We made a series circuit. For that u need to connect the LEDs to each other and then to the battery. A series circuit is defined as having only one path through which current can flow

For the parallel circuit we had to connect all the LEDs to the battery using a diode.\
A parallel circuit is one that has two or more paths for the electricity to flow.\
![](https://lh5.googleusercontent.com/HsCg5JV9e0ELismGZOit9yRoEZNxIjGG5aS7WvGXZjCyorwj8CSeCs3sCrLGKpU3UCXygU6JsL-Wxzou2I_XlVTBwza3mKBpBS4j_dAIpISWvxpdUINr7AjKDb3jIp7A3NvNnRWBO5k_ICpxpfc9Fo8)

Later on we learned basic blinking\
For that u will need an arduino uno R3, a breadboard, resistors, a push button  and 2 LEDs.\
![](https://lh4.googleusercontent.com/c8ZjNfNJUfAiD3LL8xkdlPZJCxuovxR0rZN4eO-kFh0xsSjgRce8Xc5FujggWCOoLhpdD8tVRg47BrRIHBCIQaaZGlLzaAwtygO5JnsbcOmum6GKipLo6Vj1a-pSSbxvG5XnyY4PHs4CAPexHi1RztE)

Code :\
// BASIC BLINKING

int led = 2;

int button = 3;

void setup()

  {

pinMode(led, OUTPUT);

pinMode (button, INPUT);

  }