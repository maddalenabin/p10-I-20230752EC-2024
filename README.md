# p10-I-20230752EC-2024
Scripts for data analysis of the beamtime I-20230752 EC at P10, March 2024.

Download the scripts with 
```
git clone https://github.com/maddalenabin/p10-I-20230752EC-2024.git
```

To run the scripts it is required to install [Xana](https://github.com/reiserm/Xana). You can follow the instructions in Xana's Readme to do so.

You can also create a new environment to install all the requirements with the following commands:
```
python3 --version # check that it's Python 3.8 - usually
python3 -m venv .venv
ls -a 
source .venv/bin/activate
pip install --upgrade pip
pip install -r 03-scripts/requirements.txt
git clone https://github.com/reiserm/Xana.git
cd Xana
pip install -e .
pip install --upgrade ipykernel
python -m ipykernel install --user --name p10-env
```
