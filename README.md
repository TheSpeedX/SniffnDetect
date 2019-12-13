<h1 align="center">SniffnDetect</h1>

## What is SniffnDetect ?

SniffnDetect is an advance DDOS detector tool written completely on Python3. It will sniff your network for a certain amount of time and identify attacks like:

- SYN Flood Attack
- SYN-ACK Flood Attack
- ICMP Smurf Attack
- Ping of Death
- and many more to come..

After detecting those attack packets, SniffnDetect will also find the source of the attack and provide the details of  attacker(s).

## Installation
```
git clone https://github.com/priyamharsh14/SniffnDetect.git
```

## Usage

NOTE: Script must run in root (in Linux) or Administrator (in Windows)

```
$ cd SniffnDetect
/SniffnDetect/$ python3 start.py
```

This command will run the script for 60 seconds.