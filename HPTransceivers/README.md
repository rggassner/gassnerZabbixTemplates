# HP transceivers LLD monitoring (gbic DDM DDMI DOM)

Low Level Discovery (LLD) for HP transceivers (switches) monitoring (gbic DDM DDMI DOM).

Attention: You will want to have a regular expression called @isFiberTransceiver to filter out cooper gbics (stacking, etc)

oid .1.3.6.1.4.1.25506.2.70.1.1.1.1

Triggers are created with thresholds given by gbic.

Temperature, voltage, bias, serial, hardware type, fiber diameter, status, dbm, db, transmit power, receive power.
