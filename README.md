# omron-B5T-007_HVC-P2_Python2to3

Check commit history for explaination of additions and diffs.

### Directory Structure:
- `./B5T-007001_HVC-P2_for-Python-3/` = Converted code to work with Python3 using [Python 2to3 utility](https://docs.python.org/3/library/2to3.html).
- `./B5T-007001_HVC-P2_for-Python-3___additional-changes/` = Additional method of my own creation to return a memory reference to a GreyscaleImage object instead of having to read and write to disk.  I think this would be a good feature to add to the repo, but it isn't strictly necessary.
- `./B5T-007001_HVC-P2_for-Python-master/` = Original code from [Omron Python Github repo](https://github.com/omron-devhub/B5T-007001_HVC-P2_for-Python).

### Recommendations / Nice-to-Haves for the Repository Moving Forward:
- It would be great if the "library" or "module/package" code could be put in its own
subdirectory to seperate it from the example code usage files like `execution.py`.
- It would also be convenient if this could be an installable package via the `pip`
command.
