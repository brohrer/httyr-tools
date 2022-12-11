# httyr-tools
A junk drawer of snippets and utilities to accompany How to Train Your Robot code


## Installation

1. Imagine where in your directory tree you would look if someone asked you
to find a toolbox. This is the <path>.

2. Install the tools as a local Python package. At the command line

    cd <path>
    git clone https://github.com/brohrer/httyr-tools.git
    python3 -m pip install -e httyr-tools/

3. (optional, for Mac and Linux) Add the tools to your command line path.
Open the initialization file for your command line shell.
On my system this is in `/home/brohrer/.bashrc`.
Add this line to the end of the file.

    export PATH=/home/brohrer/projects/httyr-tools:$PATH

Save it and then at the command line run your equivalent of

    source /home/brohrer/.bashrc

This will let you run shell scripts from the command line too. 

Sorry Windows users. I don't have a Windows machine on hand to develop
and test a version for you. If you make one, let me know and I'll add
it to this repository.

## Using httyr-tools

    from httyrtools.pacemaker import Pacemaker
    from httyrtools import logging_setup
