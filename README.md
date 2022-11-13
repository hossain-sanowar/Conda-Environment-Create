# Conda-Environment-Create
This project is going to create Conda Environment using the terminal or an Anaconda Prompt 

# Documents of Conda Environment
1. https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html
# Cheatsheet of Conda Environment
https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf

# "setup.sh" file to create conda environment
```
python3 -m pip install virtualenv
echo "creating a virtual envirnment."
virtualenv -p python3 virtualenv
echo "activating virual environment"
. virtualenv/bin/activate
echo "virtrual environment activated"
source virtualenv/bin/activate
```
# how to activate the command
```
chmod +x setup.sh
./setup.sh
source virtualenv/bin/activate
```
#or create in Pycharm; here, folder name is `envs`
```
conda create --prefix ./envs python=3.10
conda activate C:\test\envs
then changing the setting location in Pycharm
```
# install requirements.txt `./` means the current directory
```
pip install -r ./requirements.txt
```
