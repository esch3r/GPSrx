# GPSrx
##Reception of GPS signals from RTL-SDR and getting raw GPS data
* Using GNU radio software to realize the incoming data and plot its spectrum.
* GPS signals are well below the thermal noise, but can be received because it uses C/A signals which uses Spectrum spreading using PRN (Pseudo Random) Codes.
* By correlating the received signal (which looks like noise) by the C/A PRN code, GPS receivers receive data from satellites