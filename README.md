#Fork to try and make it suitable for PAL

# gr-ntsc-rc
NTSC receiver and transmitter for 5 GHz drones

### Dependencies

- GNU Radio v3.7.X. <br> See the [GNU Radio Wiki](http://gnuradio.org/redmine/projects/gnuradio/wiki/InstallingGR) for installation instructions.

To use osmocom_source examples with Limesdr mini the following will be needed.
Soapy sdr
https://github.com/pothosware/SoapySDR/wiki/BuildGuide

Soapyuhd
https://github.com/pothosware/SoapyUHD/wiki#building-soapy-uhd

Limesuite
https://github.com/myriadrf/LimeSuite

gr-osmosdr
https://github.com/osmocom/gr-osmosdr
### Installation

```
cd gr-ntsc-rc
mkdir build
cd build
cmake ..
make
sudo make install
sudo ldconfig
```

### Usage

Open examples/NTSC_Video_5GHz_RX.grc and examples/NTSC_Video_5GHz_TX.grc example flow graph in GNU Radio Companion.

### Disclaimer

This code is provided for educational and research uses only. The usage of this code is of sole responsability of its user. 
