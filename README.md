Embedded_Assignment

This is an Assigment completed as part of my computer science degree at the University of Kent. It is a simple C++ program built upon mbed_os libraries for use running on an embedded device. This is a simple example which uses various sensors on the emmbedded device to record its status and send these in packets to a server with various bit flags to denote different states. This takes into account multiple embedded devices trying to contact the server at the same time and subsequently has exponential back off included, along with checksums and acknowledgement flags.
