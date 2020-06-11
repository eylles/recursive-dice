# Recursive Dice

This script is a really awful way to write a dice roll in posix compliant shell tha can parse dnd dice notation.

## Install

```
git clone https://github.com/eylles/R-dice
cd R-dice
chmod +x ./install.sh
./install.sh
```
The install script will locate the script in the $HOME/.local/bin/ directory and add it to PATH in .bashrc IF it ain't already added to PATH in your system, if you have a different dedicated scripts directory already added to PATH just go there in a terminal and run:
```
wget https://raw.githubusercontent.com/eylles/R-dice/master/roll
chmod +x roll
```

## How To Use

just open a terminal and run roll like
```
roll 3d6
```
this will roll 3 dice each with 6 sides

```
roll 3d6 +3
```
this will roll again 3 dice each with 6 sides but will add 3 to each side
 

## Okay, but why tho?
at first it was "muh posix meme", then it was "muh minimalism", then it was didactic but at the end this terrible thing was definitely driven by self hate, otherwise i would had stopped at using a while loop...
