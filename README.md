# File_Extraction

A Python script to collect *.* files from subfolders and consolidate them into a single target folder for streamlined file management.

This script automates the process of gathering .gff files from multiple subdirectories within a specified main directory and copies them into a designated folder named gffs. It ensures efficient organization by consolidating all .gff files in one place for easier access and management.

## Usage:

1- Specify the path to the main folder containing subdirectories in the source_folder variable.

2- The script will create a folder you named inside the main directory if it doesn't already exist.

3- It will iterate through each subfolder, identify .* files, and copy them to the folder you named.

4- The console will display the name of each file and the respective subfolder from which it was copied.
