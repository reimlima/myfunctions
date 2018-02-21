# myfunctions
--------------------------------------------------------------------------------

Tiny functions to help you in your working day

# Dependencies
--------------------------------------------------------------------------------

You have to have this packages installed to work well with some functions

* [rdesktop] to access Window Remote Desktop
* [jq] command to parse Json

# Examples
--------------------------------------------------------------------------------

```sh
# How to Start

$ source myfunctions

# Functions ready to use

$ myfunctions
mfinstall : Install myfunctions on bashrc to run your functions as you open a new terminal
myfunctions : Show functions in the file .myfunctions with a brief description of what they do
pagestatus : Return the HTTP status code from the given url
mincalc : Time sum based on the array of minutes given
dropthejar : Add rules in iptables to block HotJar
percentage : Simple Percentage calculation
go : Launch a remote server access via ssh or rdesktop
geoipfetch : Geo Localization from a Given IP Address or Site URL
formulaone : Show informations about the winner of the last race in F1

# Install

$ mfinstall
Myfunctions was installed successfully
```

### After install it, open a new terminal and let the fun start

```sh
# Look for the origin of some ip addresses
geoipfetch 172.217.29.174
United States
geoipfetch google.com
United States

# Calculate your overtime work hours
$ mincalc 00:30 00:54 00:26
00:01:50

# Find out the amount of percentage did you read of your book
percentage 192 388
49.48453608247422680400
```

# Enjoy!

[//]: #
[rdesktop]: <https://github.com/rdesktop/rdesktop/releases>
[jq]: <https://stedolan.github.io/jq/>
