# Introduction #

Carlos in the Brody lab is currently (June 09) working on upgrades to the RTL code.


# Details #

Three main things are being done:

  * The most important: going through Calin's code and making [notes](notesOnCode.md) so that we understand it and others can work on it. This'll greatly facilitate opening it up for future improvements.
  * DIO scheduled waves will have the capacity to loop automatically, if so desired.
  * DIO scheduled waves will now be able to trigger other scheduled waves
  * State transitions will now be able to occur on conditions (e.g., "is input line 3 high?") in addition to the current capacity, punctate events (e.g., "did line 3 just change from low to high?")
  * A general framework to easily add new transition types is being constructed

All of these are on the non-embedded C capable side of the code. We'll get to the embedded C later.

The enhancements should be posted in a week or two -- beginning of July.