# tec-lab
Interactive lab building sessions with the TE commons and the TE community.

## Step Number 1
Cloning the lab repository onto your system:

Copy the clone url by hitting the green button and copying, then use git:
```
git clone https://github.com/TECommons/tec-lab.git
```
Or use the windows git gui.

## Step Number 2
Create a virtual environment:

```
pip3 installl virtualenv
python3 -m venv tec-venv
source tec-venv/bin/activate
```
Or be a legit hacker and use the fish shell and virtualfish:
```
vf new tec
```
Install the requirements with pip:
```
pip3 install -r requrements.txt
```
If you have issues installing cartopy try the solutions here: https://stackoverflow.com/questions/53697814/using-pip-install-to-install-cartopy-but-missing-proj-version-at-least-4-9-0 

If you really can't get it then just delete cartopy from requirements.txt, it's just used for geo mapping.

## Step Number 3
Make sure you have the pyviz jupyter lab extension:
```
jupyter labextension install @pyviz/jupyterlab_pyviz
```

Run jupyter
```
jupyter lab
```

## See the Notion Workspace for more information

https://www.notion.so/saa108/Token-Engineering-Commons-Lab-c1c1f5dc4b40423cbc65bea6fd9df96f 
