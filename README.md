# CSVtoTXTscripts
Get text out of CSV files and into TXT files

## Use
This is a pretty basic collection of scripts that will dump texts out of CSV files and into TXT files. If you're looking for a GUI-driven program to do the same, you might want to check out EZPZTXT: https://ezpztxt.ryanb.cc

### Python Scripts

#### CSV to Text.py
This script will prompt you for the columns to be used as filenames (usually some kind of subject/participant identifier),
as well as which column contains your text samples.

#### CSV to Text - 20000 Files in Subfolders.py
This script does the same as the one above it, but puts all .txt files into subfolders with a maximum number 
of files in any given folder set to 20,000. Use this for extremely large datasets so that you don't get folder bloat.


### R Scripts

#### CSV to Text Files.R
The "R" equivalent to the python script above.
