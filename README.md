# This is the code of the Atlas Team based on the Thalos Team Open Source Code

## Running the code

### 1. Clone the repo

``` bash
git clone https://github.com/iita-robotica/rescate_laberinto.git
```

### 2. Install dependencies

Latest Erebus version at the time of uploading: 23.0.5

Python version: 3.10

Dependencies:

``` bash
numpy==1.23.5
opencv-python==4.7.0.72
scikit-image==0.20.0
imutils==0.5.4
stickytape==0.2.1
```

Install them all with:

``` bash
pip install numpy==1.23.5 opencv-python==4.7.0.72 scikit-image==0.20.0 imutils==0.5.4 stickytape==0.2.1
```

### 3. Load the robot

Go to the directory ```robot_jsons``` and pick the one with the highest number.

### 4. Run the code

To run our code you can load the ```compiled.py``` python file. This is a file compiled with the python module ```stickytape```, to run the code easily.

If you want to exepriment with the code and modify it, first run ```python ./scripts/update_path.py```. Then go to the ```/src``` directory. There you can load the ```run.py``` file as the erebus controller.
In the ```flags.py``` file you can turn on and off the debug information, so you can see how everything works under the hood. If you activate any debug, set the ```DO_WAIT_KEY``` flag to True also.

## Old code from previous competitions

If you want to look at our old code, you can go to the directory ```/previous_competitions/Competencias```. Be aware that some parts might be in Spanish.

## Testing Environment

We developed a system to autamatically do massive tests on our code and give statistics about it's performance in different maps. You can find that in this repository: https://github.com/iita-robotica/testing_simulator

## License
Our code is free and open-source under the MIT license! That means you can do whatever you want with it. We encourage you to see our code, take inspiration and copy it. You can also make your own fork of this repsitory and share your innovations upon it. We are exited to share and innovate together, and in this spirit we would like to encourage you to do the same, so we can all grow together. Only one thing: if you end up copyign entire modules as-is, it would be nice if you gave us some credit ;).

