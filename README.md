# task1
A:
python taskA.py

B:
cmd1 : python app.py
cmd2 : python process.py

C:
dockerhub command : docker pull ihsanur77/taskdone

cmd: docker run -d -p 5000:5000 --name taskdone5000 taskdone
     docker run -d -p 5001:5001 --name taskdone5001 taskdone
     python process.py
     python process5001.py
