# PyCAPCOM

Python class to manage multiple demands on a single resource.

It was built to manage communication for a serial communication bus, where
multiple pieces of code wish to communicate multiple messages with mulitple
devices all on a shared serial port. Messages are tracked by priority and
sent in that order to prevent access collision on the single port.

Named after NASA mission controller position [CAPCOM](https://en.wikipedia.org/wiki/Flight_controller#Spacecraft_communicator_(CAPCOM))
who is the only voice talking to the astronauts in space. So there is only one
conversation over radio and CAPCOM is responsible for ensuring highest priority
information are communicated first.
