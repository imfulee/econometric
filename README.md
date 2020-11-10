# Econometric

Just a homework repository for my Econometric course. 

## How to use this

This is a tutorial on how to setup `python`, `pip` and `venv`. So if you know how to use it, then promptly skip this part. I would write this for `Windows` and `Mac` only, because `Linux` and `BSD` users could probably figure it out anyways. (\# Fedora User)

> If you don't understand what I'm talking about you could go find the relevent information on the internet or just not care and follow along

1. [Download Python](https://www.python.org/downloads/) and [install it in your PATH](https://datatofish.com/add-python-to-windows-path/)
2. Open up your terminal (`Windows` -> `Powershell` and `Mac` -> `Terminal`) and change the current directory

```bash
cd <dir> # replace <dir> with the correct directory
```
For example my folder is called econometric and is saved inside the Documents folder.
```bash
cd .\Documents\ecnometric # Windows
cd ~/Documents/econometric # Mac
``` 

3. Type either one of the following commands (Whatever works for you.) to setup your `virtual environment` and activate it. 

```bash
py -m venv . # or
python3 -m venv .
```

> If you have errors now, check if Python is on your PATH

4. Activate your `virtual environment`

```bash
.\Script\activate # Windows
source bin/activate # Mac
```

5. Download the required packages with `pip`

```bash
python -m pip install -r .\requirements.txt # Windows
pip3 install -r requirements.txt # Mac
```

6. Startup `Jupyter Lab`

```bash
jupyter-lab
```