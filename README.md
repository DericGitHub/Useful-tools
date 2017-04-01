# Useful-tools
## Foreword
To speed up our work process and to practice python skill, I propose to build a series of executable automated scripts by following our standard debug process.

## Tool list
Name|Version|Brief
-|-|-
J49|v0.2.1|Translate errlog to readable text
Jsim|v0.2.0|Setup simulator environment and preview output file

## Usage
* J49
```
Usage: python J49 -p <IP> -m <map file> [-o <output file>]

Options:
  -h, --help            show this help message and exit
  -p IP, --ip=IP        IP of which printer you want to check
  -m MAP, --map=MAP     the full directory of *.map, e.g.
                        '/projects/phx/nightly/puma.mon.debug/puma.map'
  -o OUTPUT, --output=OUTPUT
                        output file name, the error address and related
                        function name will be recorded into this file
```
* Jsim
```
Usage:run 'setup_sim <test file>' in you scm directory
```
## Change Log
* 2017.03.31
	* submit J49 v0.1.0 and Jsim v0.1.0

* 2017.04.01
	* J49 v0.2.1
    	* Basic function implemented.Now we are able to fetch the raw error message from http://<IP>/hp/device/developer/errorLog.html and translate it to readable call stack information.
    	* Help message added.
		* Remove useless output message.
	* README.md initialized.
	* Jsim v0.2.0
		* remove scm path parameter when execute program.Now we need to run Jsim in your target scm directory.
		*Remove unnecessary code.


## Bugs
## Notes
## FAQ
