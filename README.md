# ACI

ACI - Arduino Client Interface is a bash environment to develop and distribute arduino projects.

![](https://media.giphy.com/media/XHnsiy7sF3tnrpHSPQ/giphy.gif)

## Features
ACI features include: 
* project's variables managing
* arduino fqbn autosetup 
* package-managing
* compiling
* uploading
* serial port monitoring
* debugging
* distributing

## Getting Started


### Prerequisites

The following packages are required on your Linux machine

```
arduino-cli (https://github.com/arduino/arduino-cli)
jq
grep
```
On Arch Linux, you can install prerequisites by command
```
yaourt -S arduino-cli grep jq
```

### Installing

```
git clone https://github.com/tri2820/aci
cd aci
./aci install
```

### Running

```
mkdir example_arduino_project
cd example_arduino_project
source aci
help
```

## Built With

* [arduino-cli](https://github.com/arduino/arduino-cli) - Heavily dependent for all sorts of things

## Versioning

0.1

## Demo
* [Setup a project](https://asciinema.org/a/U39u1S9LSysYxxgOKW8uE5437?speed=1.7)
* [Package managing](https://asciinema.org/a/hArXx60xcG2lpHKEJrO6rMXgR?speed=1.4)
* [Help](https://asciinema.org/a/Jhx6keqB2vHV8PyHRrVPLHgm1)
