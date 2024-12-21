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

and learned how to use the mannual command option to study more options of any command 
example #man date will explain you all the diffrent types of options to use command 

after that we study top and htop command which is use to check continously the status of the programs using the cpu and memory useage 
then we test the nice and renice command to modify the prioprity of any program and the running program 
later we discussed about the RES  which is resident address explained the how much memory used by the programe

then the other diffrent options like kill any program from the top status of utilizing memory by the program

later we started the BASH SHELL Script topic and revise the concept of shell scripting variables, reading value from user and storing the command output to the variable and use it later we get to know the power of "&" which is use to run multiple command at a time and gedit etc 

free command is used to check the free space on the RAM. Sometimes if we start some application or some process space before that is more and after starting the program it may be less than the previous because some space is occupied with some garbage waste which gets cleared and due to which space gets more after the startup.

lscpu command will tell how many CPUs are in your computer and even it will tell how many hardware threads.

