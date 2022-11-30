# factorio-cli
simulated factory building, rocketeering, and wizardy

Project Goals:

build a powerful CLI to support a factory simulation.
inspire optimization.
experiment with time
enable fast iteration of ideas
learn stuff by writing cool software

Needs:

Testing


## implementation
- built with [cmd2](https://github.com/python-cmd2/cmd2), an extension of [cmd](https://docs.python.org/3/library/cmd.html) from the python standard library 

- data extraction done using [Data Exporter to JSON](https://mods.factorio.com/mod/recipelister) mod by Erythion.

## local setup 

$ python3 -m venv venv
$ source venv/bin/activate
$ pip install flask requests cmd2

flask --app server run
python3 ./main.py


https://www.b-list.org/weblog/2022/may/13/boring-python-dependencies/
