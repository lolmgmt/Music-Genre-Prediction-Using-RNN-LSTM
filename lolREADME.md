# Instructions
```
# clone this repo
cd /path/to/cloned/repo
./dev.sh
# this will download the python docker image, and start a container sleeping forever. it'll look like the terminal is hanging. 
# open a new terminal
docker exec -it genre-classification bash
cd /code
pip install -r requirements.txt
```