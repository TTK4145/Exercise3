# Exercise 5: Call for transport

If you have completed the last assignment you will already have a working network module. This means that som parts of this exercise will be familiar to you as the elevator hardware exposes a tcp interface.

Testing the software you're writing is an essential part of being a developer. Whether you're automating the tests by coding the them or taking a more manual approach you should never be confident that a piece of software is working before you've tested it. Those of you that have dabbled in embedded software should already know that when hardware is involved, testing reaches a whole new level of complexity. A lot of the time you don't want to run experimental builds directly on the hardware you're developing for. Because if you do hardware might be damaged or people might be injured or killed. To kill anyone with the hardware you're using in this project would require more creativity and bad luck than I hope any of you possess. But there's another problem present. The elevator hardware is a limited resource. There's 25 elevators distributed amongst almost 100 lab groups and every group need 3 elevators. To avoid the problem that only 8/100 groups can develop at any given time a simulator has been made.

The recommended workflow for this project is the same one you will be using in this exercise. You first develop your code while testing in simulation, when you're certain your code work as intended you run it on the hardware.

## Parts
- [Part 1: Initial testing](./Part1/README.md)
- [Part 2: Writing elevator code](./Part2/README.md)
- [Part 3: Completing the abstraction](./Part3/README.md)


## Approval
This exercise does not require excplicit approval as it's implicitly improved when you complete the project.
