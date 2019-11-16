# LTC Reader

## A generic basic LTC decoder

LTC stands for Linear Timecode and is a signal used in media production to time synchronize multiple sources of audio and video involved in same production.

LTC is an analog audio signal and because of it can be easily transmitted among stations.

As faster your sound card driver is, minor is the jam interval.

This script needs some improvements, but the main feature (read timecode) is working perfectly.

## Usage

Import module in your script and call `start_read_ltc()`

    import ltc_reader
    ltc_reader.start_read_ltc()
