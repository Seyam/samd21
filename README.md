# PubNub for Atmel's SAM D21 Usage Notes and Client SDK Examples

The examples in `examples` directory are using the Atmel's ASF libraries. No RTOS is used.

The Pubnub client is derived from the Contiki OS client, using the winc socket interface.
It's source code is in `examples/Code/pubnubAtmelExample/src/Pubnub.c`. In the header (`Pubnub.h`) there are a few macros that the user can change to suit a particular application (buffer sizes, etc.).

Detailed instructions on how to connect all the HW, compile & upload the SW/FW and run the examples are in `examples/README.md`.
