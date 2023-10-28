# showorb.vmd

**the script for vmd, modified from [TianLu's Multiwfn](http://sobereva.com/447)**

## functions

Here are the four functions it contains

- [] proc orb {folder_path iorb}

- [] proc orbiso {isoval}

- [] proc orbclean {folder_path}

- [] proc orbrender {folder_path start_orb_index end_orb_index isoval scaling_factor}

Where I added the orbrender for multiple rendering process. To control the the resolution and renderer, I used the variable renderer and the command line `display resize 2560 2560`, the `render $renderer $filename`.

**one thing should be noticed is that the variables in tcl is not global(maybe?) between different proc.**
