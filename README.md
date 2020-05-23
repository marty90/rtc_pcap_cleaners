# Zoom PCAP Cleaner

Clean a capture file to make Zoom RTP flows look like standard ones.
To do this, the tool decapsulates the RTP packets from the custom Zoom transport protocol.

Prerequisites: you need Python3 with the `dpkt` package installed.

Usage: 
```
zoom_pcap_cleaner [infile] [outfile]
    If outfile is omitted, print on the standard output.
    If infile is omitted, read from the standard input.
```
