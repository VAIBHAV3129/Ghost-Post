# Ghost-Post// RP2350 Encrypted Node
Core: Raspberry Pi Pico 2W

Project Overview
Ghost-Post is designed to be a high security, offline communication terminal, allowing users within a range of about 10m to exchange encrypted messages without ever touching the public networks which might not always be very safe.
By utilizing the Raspberry Pi Pico 2W (RP2350), Ghost Post creates a local WiFi captive portal, I believe it will serve a highly useful purpose and an excellent solution for environments where privacy is very often compromised of the connectivity is non existent.

But you might wonder why Ghost-Post
In the modern era, the digital footprints that you are me leave behind are permanent and I wanted to build a device that facilitates ephemeral communication, the solution?, well the idea is to create a physicl node that stores data only in its local, encrypted flash memory, if either the device is removed or if the nuke button is pressed the data just vanishes for ever.

The Architecture and the specs
Unlike the standard microcontrollers , thr RP2350features a dedicated Hardware SHA-256 and AES- 256 engine, Ghost-Post leverages these features to encrypt messages at the hardware level. and also protects side channel analysis that the software only analysis might leak.

Mechanical Integrity
***
