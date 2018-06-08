# file_processing

The main objective of this repository is to provide many different reading methods in order to abstract the library that is used to read. 

## PCAPS
The first reading method implemented is for pcaps, which allows you to:
- read any pcap, pcapng file or similar
- extract TCP only or TCP and UDP payload from a packet
- return a list of all packets contained in a pcap in order to iterate over them
