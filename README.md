# X11
The configuration for 5 monitors at NSLS2 10ID beamline xf10id-ws2.
Four of the monitors are Dell 4k, and the 5th is a LG TV with 4k resolution.

-----------
SSH pass through beamline box64 gateway system.
The config files is placed in .ssh/config in user home directory and allows "hopping directly to the beamline linux computers.

1. Generate key { ssh-keygen -t rsa}
2. copy kaz.pub key to box64 system in home directory. The home directory is nfs mounted and thus is accessible on all beamline computers.

