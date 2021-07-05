# Instructions
```
# clone this repo
cd /path/to/cloned/repo

# download Dataset (GTZAN)
https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification

# unzip dataset

# start docker container. The following command will download the python docker image, and start a container sleeping forever. it'll look like the terminal is hanging. 
./dev.sh

# open a new terminal
docker exec -it genre-classification bash

cd /code

# install a required system dependency
apt update && apt install libsndfile1-dev

# install project dependencies
pip install -r requirements.txt

# run code to extract features from Data (music from x different genres)
python 'Data Preprocessing.py'
```