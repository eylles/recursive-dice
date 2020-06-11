# Recursive Dice

This script is a really awful way to write a dice rolld in posix compliant shell tha can parse dnd dice notation.

## Install

```
git clone https://github.com/eylles/recursive-dice
cd recursive-dice
chmod +x ./install.sh
./install.sh
```
The install script will locate the script in the $HOME/.local/bin/ directory and add it to PATH in .bashrc IF it ain't already added to PATH in your system, if you have a different dedicated scripts directory already added to PATH just go there in a terminal and run:
```
wget https://raw.githubusercontent.com/eylles/recursive-dice/master/rolld
chmod +x rolld
```

## How To Use

just open a terminal and run rolld like
```
rolld 3d6
```
this will rolld 3 dice each with 6 sides

```
rolld 3d6 +3
```
this will rolld again 3 dice each with 6 sides but will add 3 to each side
 

## Okay, but why tho?
at first it was "muh posix meme", then it was "muh minimalism", then it was didactic but at the end this terrible thing was definitely driven by self hate, otherwise i would had stopped at using a while loop...
