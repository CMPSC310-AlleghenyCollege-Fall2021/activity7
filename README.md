# activities 7: Starting with OpenCV

## Locally Installed OpenCV

If you have OpenCV installed locally on your machine, you can run Python programs directly
from the terminal, as specified in each sample program.


## Docker

Once you have Docker Desktop running on your machine, you can use Docker to run given
Python programs that use OpenCV.

### Building

First, inside `activity7` directory, run the build script inside `docker` subdirectory, that correspond to your OS. For example, in Mac, you would run:

`sh docker/build_macOS.sh`

This creates a new container called `opencv`.

### Running

To run each program in a docker container, run the run script corresponding to your OS. For example, in Mac, you would run:

`sh docker/run_macOS.sh`

Now you can navigate to `src` directory and run each Python programs inside your container.

### Output

The output of each program is stored in the directory corresponding to the program name. See the source
code for more information.

## Tasks

- Run `imageDisplay.py` on one of the flint images.
- Using ideas from `drawing.py`, create `Canvas3.png` of your own design.
- Ysing idead from `transformation.py`, perform several transformation of one of the flint images.
