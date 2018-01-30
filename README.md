# GOOS notes
Notes and code related with the book "Growing Object-Oriented Software, Guided by Tests".
* It uses an Outside-In approach, at the same time that a classicist style (it only uses Spies, but no Mocks or Stubs, it uses the real implementations in the tests).

## My notes
* Write an Adapter Layer.
* Mock Application Objects in Integration Tests: mock the callback interfaces.
* An important part of the test-driven development skills is judging where to set the boundaries of what to test and how to eventually cover everything.
* Null implementaton vs Null object
* Encapsulate collections
* Defer decisions
* Keep the code compiling
* Only mock types that you own
* Not too small to test
* Celebrate changing your mind
* Describe behaviour, not API features
* Object peer stereotypes:
    * dependencies
    * notifications
    * adjustments: peers that adjust the object's behavior to the wider needs of the system.
* Ports (interfaces) and Adapters: anticorruption layer
* Domain types are better than Strings
* Small methods to express intent
* Logging is also a feature.


## Techie stuff
* XMPP broker: OpenFire + Smack library
    * https://hub.docker.com/r/gizmotronic/openfire/
* Swing test framework: WindowLicker


## What would I do differently?
* The naming for the assertion tests in the end2end test: always a prefix like "verifyXxx" o "checkXxx".


## Links
* http://www.growing-object-oriented-software.com/
* http://www.growing-object-oriented-software.com/code.html

## Source code
* https://github.com/sf105/goos-code
* https://github.com/npryce/goos-code-examples

## Pending to be read
* https://gojko.net/2010/03/28/brian-marick-mocks-lead-to-better-design-faster/