CopyImagesToDirectories
=======================

This python script copies image files over into a hierarchy based on date. This script requires that the Python Imaging Library be installed. This scripts copies the JPG, CR2, and MOV files one directory (not including subdirectories) to another directory. The script expects an input directory and an output directory as agruments. There is also an option to use two output directories. The heirarchy structure of the output is listed below.

/output_directory/YYYY/YYYY_MM/YYYY_MM_DD/

Usage:
```python CopyImagesToDirectories.py /input_directory/ /output_directory/```
