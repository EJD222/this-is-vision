# Installing Vision by Daguio, Diaz, and Tabual
# Please ignore this if the app can be pre-installed. (In this case the file of the app is pre-installed ready together with YOLOv5, you only need to pip install the necessary imports.)
- The use of Anaconda is prefered.
- `git clone "github_link"`
- cd <newly Created folder>
- `conda create -n envyolov5 pip python=3.9` or `python -m venv envyolov5`
- `conda activate envyolov5` or `.\envyolov5\Scripts\activate` for Windows 
- RUN
    For Windows `python ./yolov5setup.py`
- `cd yolov5`
- RUN `streamlit run app.py`
- Error handling: 
    - After running the above script,  if `no module error` is occured then just find the relevent `pip install <module name>` command and run it
- Other useful commands
- `conda env remove -n ENV_NAME`
- `conda env list`
- `python.exe -m pip install -r tfod1_requirements.txt --user`
- `conda list`




