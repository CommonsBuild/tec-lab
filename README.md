
🌈!

# TEC Labs!
Interactive lab building sessions emerging from the TE commons and the TE community.

Read the proposal here:

https://forum.tecommons.org/t/tec-labs-production-team-funding/201 


## Getting started

### Clone the lab repository onto your system and enter it:
```
git clone https://github.com/TECommons/tec-lab.git
cd tec-lab
```

### Create a virtual environment:
Make sure that you have python poetry installed: https://python-poetry.org/docs/
Install the requirements as per the poetry.lock file:
```
poetry install
```
Activate your poetry shell:
```
poetry shell
```

Run jupyter
```
jupyter lab
```

### See the Notion Workspace for more information or to learn how to contribute:

https://www.notion.so/saa108/Token-Engineering-Commons-Lab-c1c1f5dc4b40423cbc65bea6fd9df96f 

## Below this line is deprecated. We will remove it if we can come to community consensus on using python poetry.

If you don't want to use poetry you may use the traditional python virtualevn:

```
pip3 installl virtualenv
python3 -m venv tec-venv
source tec-venv/bin/activate
```

Or you might use the most worful fish shell and virtualfish:
```
vf new/activate tec-lab
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
