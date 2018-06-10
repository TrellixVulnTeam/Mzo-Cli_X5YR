# Monzo Cli
A (third-party) command-line interface to your monzo account. 
Because _Sometimes_ the command-line is more convient then 
swiping and tapping.

This README covers the enviroment setup if you are looking to
run the applications source code / work on the project. If you
are looking for the documentation and more straight forward
installation instructions [see the docs](https://jamesstidard.github.io/Monzo-Cli/).

## Prerequisets
At the time of writing this the project is using Python 3.4.6.
You will need that version of python installed before starting.
If you don't currently have a method of managing multiple Python
versions on your machine, I would recommend checking out [pyenv](https://github.com/pyenv/pyenv).

The projects dependancies are also managed by [pipenv](https://docs.pipenv.org/).
You should head over there and make sure that you also have that
tool setup.

## Summoning Ritual
Once you've completed the prerequisets above you should be able
to bring the application to life with the following commands.

```bash
# clone the source code to your machine
$ git clone https://github.com/jamesstidard/monzo-cli

$ cd monzo-cli/

$ pipenv install --dev --python 3.4.6
```
