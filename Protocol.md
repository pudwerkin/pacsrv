# Introduction #

The clients and servers will need to communicate with each other.

# Requirements #

  * Simple protocol that is easy to implement
  * Flexible, so that additional functionality can be added.
  * Version agnostic.  Additional features should not cause problems with older versions of the server or client.

# Details #

The protocol will use a RISC based approach were each operation is broken up into seperate commands that can contain one parameter of a fixed type.