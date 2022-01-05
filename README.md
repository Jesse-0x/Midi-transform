# Midi-transform
A python script can transcript MIDI to json format

the out file format will like this

```json
{"songNotes": [{"time": 0, "key": "1Key0"}]}
time: normal time * 1000
key: 1Key0-1Key14
```

Basiclly it ransform into this format then you can play inside `Player.lua` on your phone. Need a tool E.G. Autotouch on your phone to play the script.

### Usage

```
usage: Sky [-h] [-n NAME] [-r NRANGEC] [-o OUT] [-a ALL]

A little tool for script trans.

optional arguments:
  -h, --help            show this help message and exit
  -n NAME, --name NAME  input file name(optional)
  -r NRANGEC, --range NRANGEC
                        The range of file(not suggest to use)
  -o OUT, --out OUT     Special out file name(default *.mid.txt)
  -a ALL, --all ALL     Output all the range of file
```

