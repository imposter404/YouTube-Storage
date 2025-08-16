# Youtube As Storage
## Objective
To use Youtube as Unlimited Storage Server for Free !!!
---
## Disclaimer
This is for Educational Purpose Only <br>
plz Dont Crash Youtube Server :)


---
# Setup
## Python Dependency 
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pypi/pypi-original.svg" height="50px" alt="pypi" />

> ``` console
> pip install opencv-python
> pip install numpy
> ```



---
# Process 
### Encoding
The `file_input.txt` is the main text file user gives <br>
then this text file is encoded and converted into `.png` image and stored in folder `/en` <br>
after that all the `.png` images is converted into a video file named `a.avi` <br>

### Decoding 
Firstly the video `a.avi` is taken then each frame is extracted and converted into a `.png` file 
and stored into the folder `/de`. Then each frames are decoded back into text format and stored into `file_output.txt` 

---
# Concept
This is an Extention of my project [/Encoder]('https://github.com/imposter404/Encoder')<br>
for more information look into that Github Repository
---
# Setup
The `requirements.txt` file should list all Python libraries that your code
depend on, and they will be installed using:

```
pip install -r requirements.txt
```
---
## Run
Jupyter Notebook
``` python 
Main.ipynb
```

