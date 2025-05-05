# bmm_xspress3_settings

These settings were hand crafted for BMM elderly 4-channel Vortex
silicon drift diode detectors by Liam from Quantum Detectors way back
in 2022.

These xspress3 calibration files lived in
/etc/xspress3/calibration/8_channel/epics_setttings/ on the old
xf06bm-xspress3 server.  That machine has since been retied and the
IOC runs on xf06bm-ioc2.  These configuration files along with those
for the 1-element detector and the new 7-element detector now all live
on xf06bm-ioc2.

Because the configuation for the 4-element detector is so difficult,
we are preserving these files here.

The sense in which this is difficuolt is that the normal calbration
routines failed badly for one of the channels on the 4-element
detector and worked poorly on 2 of the other 3 channels.  Getting that
tired old detector calibrated correctly required special knowledge of
the engineer from Quantum.

