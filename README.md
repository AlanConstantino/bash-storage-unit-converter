# bash-storage-unit-converter
A simple storage unit converter written in bash.

## What is this?
A simple command line tool written in bash to convert storage units into other storage units.

## Usage
```
NAME
        con - convert storage units into other storage units

SYNOPSIS
        con [number] [unit #1] [unit #2]

        [number]  - number to convert
        [unit #1] - the original unit
        [unit #2] - the unit to convert to

UNITS
        b  - bits
        B  - bytes
        Gb - Gigabit
        GB - Gigabyte
        Kb - Kilobit
        KB - Kilobyte
        Mb - Megabit
        MB - Megabyte
        Pb - Petabit
        PB - Petabyte
        Tb - Terabit
        TB - Terabyte

EXAMPLES
        con 5 Mb b
                Converts 5 Megabits (Mb) to bits (b)

        con 1.5 TB GB
                Converts 1.5 Terabytes (TB) to Gigabytes (GB)

        con 500 Gb KB
                Converts 500 Gigabits (Gb) to Kilobytes (KB)

        con h
                Brings up the help menu
```

## Install
1. Clone this repo

    ```git clone https://github.com/AlanConstantino/bash-storage-unit-converter.git```

2. Give the script executable permissions.
   
   ```chmod +x con```
   
3. Place ```con``` script in the ```/usr/bin/``` repository.

    ```sudo cp con /usr/bin/```

## Uninstall
```sudo rm /usr/bin/con```