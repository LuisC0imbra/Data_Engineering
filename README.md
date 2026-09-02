# Data_Engineering

# Fun2Know


1) You can write "python" to transform powershell terminal into python

## 1. Data Engineering Study - ZoomCamp


### a) Links

ZoomCamp Github - https://github.com/DataTalksClub/data-engineering-zoomcamp
ZoomCamp Youtube - https://www.youtube.com/watch?v=lP8xXebHmuE&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb&index=11


## 1.1 - Docker for Data Engineering: Postgres, Docker Compose, and Real-World Workflows

docker run hello world

docker run ubuntu
→ Creates and runs a container from the Ubuntu image

docker run -it ubuntu
→ Creates a container and lets me interact with it

ls
→ Lists files/folders in Linux

python3
→ Runs Python 3 (if installed)

Key concept:
IMAGE → template
CONTAINER → running instance created from an image
HOST → my actual computer


### Lets us create a container ubuntu and the "-it" part basically says let me write commands inside of it 
docker run -it ubuntu
# Then we saw if it had python with python3
# It didnt have so we installed with apt install python3
# if we want to use it , then we write python3 and it goes to python , if we want to get back to the ubuntu container we write exit()
# To exit a container (ubuntu for example we press CTRL+D)