<!-- Init mylib Packages -->
pip install -e .

<!-- Install Requirments -->
pip install -r .\requirements_dev.txt

<!-- Upgrade PIP -->
python -m pip install --upgrade pip  

<!-- Activate VENV -->
.\venv\Scripts\activate       

<!-- Install PyInstaller from PyPI: -->

pip install pyinstaller

<!-- Go to your program’s directory and run: -->

pyinstaller yourprogram.py

<!-- This will generate the bundle in a subdirectory called dist. -->

pyinstaller -F yourprogram.py

<!-- Adding -F (or --onefile) parameter will pack everything into single "exe". -->

pyinstaller -F --paths=<your_path>\Lib\site-packages  yourprogram.py

<!-- running into "ImportError" you might consider side-packages. -->

pip install pynput==1.6.8

<!-- Python comes with an ensurepip module1, which can install pip in a Python environment. -->

C:> py -m ensurepip --upgrade

<!-- This is a Python script that uses some bootstrapping logic to install pip.
Download the script, from https://bootstrap.pypa.io/get-pip.py.
Open a terminal/command prompt, cd to the folder containing the get-pip.py file and run: -->

C:> py get-pip.py

