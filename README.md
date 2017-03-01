#Snorter

Tricky script which mades Snort installation simply as a script execution is. The script installs:

+ [Snort](https://snort.org/): Open Source IDS.
+ [Barnyard2](https://github.com/firnsy/barnyard2): Interpreter for Snort unified2 binary output files.
+ [PulledPork](https://github.com/shirkdog/pulledpork): Snort rule management.
+ [WebSnort](https://github.com/shendo/websnort): Web Interface for PCAP analysis.

Successfully tested in:

+ Raspberry Pi + Raspbian Jessie
+ Kali Linux Rolling Release
+ Debian 8.5
+ Ubuntu 16.04
+ Ubuntu 14.04

***

###Download

Simply run on your terminal:

~~~~bash
git clone https://github.com/betmenwasdie/Snorter.git
cd Snorter
~~~~

###Execution

Printing the USAGE:

~~~~bash
sudo ./Snorter.sh -h
~~~~

OR

~~~~bash
sudo ./Snorter.sh --help
~~~~

RECOMMENDED: Executing the script using an [OINKCODE](https://www.snort.org/oinkcodes)

~~~~bash
sudo ./Snorter.sh -o <oinkcode> -i <interface>
~~~~
