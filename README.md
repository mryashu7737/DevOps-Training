# DevOps-Traning

Install OS by 4 methods
  1.Bare Metal
      for High performance but we can only use one at a time. 
  2. Virtualization
      Hypervisor(oracle virtual box, vm ware, hyperVisor etc
  3. Cloud Computing
      AWS,Azure,GCP etc
  4. Containerization
      Docker, k8ts etc

  some commands 
    #Firefox  #date 
    Terminate program ctrl + c 
    and hangup  ctrl +z (pause ) for check the pause program by #jobs

Checking how much RAM and cpu is using by our program by #ps -aux
if you want to resume the program which you hang up for that first find the id of that program by checking which by #jobs and then for resuming we will use the forground command with there id "#fg 1"

for those process which are not started by CLI fg command will not work for them and for them we have to find first the process id 
by #pgrep firefox then it will provide you a id example 5202 then we have to use kill command with signal number 
example for kill use -9, for stop use -19.




