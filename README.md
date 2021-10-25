# DVC -DL-TF

## commands------------------------------------------------

'''bash
conda create --prefix ./env python=3.7 -y
'''

''' source activate ./env python
'''

# init DVC
''' bash 
git init
dvc init
''' 

### create empty files
''' bash
mkdir -p src/utils config

touch dvc.yaml setup.py README.md .gitignore param.yaml src/__init__.py src/utils/__init__.py config/config.yaml
src/stage_01_load_save.py src/utils/all_utils.py 
''' 


