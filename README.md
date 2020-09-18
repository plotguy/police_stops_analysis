# police_stops_analysis

Follow code from the command line to get data / load jupyter lab:
```
# Get the data
mkdir data
cd opp
./download -t csv -s SC -o ../data/
cd ../
unzip data/sc_statewide_2020_04_01.csv.zip

# Loading Jupyter Lab
pip3 install jupyterlab
cd analysis
jupyter lab
```