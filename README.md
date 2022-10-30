<h1>CMPE 283 Assignments</h1>
<h3>By Ravi Kumar Tanti and Saurabh Ramesh Warathe</h3>

<h2>Assignment-01</h2>

<h3>Work done by Ravi (015267200):</h3>
I worked with Saurabh for this assignment. On my machine, I retrieved the .c program which was updated by Saurabh and added definitions for the different capability info regions by referring the latest Intel SDM. I also added four remaining rdmsr VM features code. I then created an Ubuntu 22.04.1 VM on my laptop through VMWare Workstation 15. I installed required packages onto it but faced multiple issues on the VM while executing make command, Therefore to overcome we reinstalled the headers and make and rebooted which solved our problem. <br>

<h3>Work done by Saurabh (015267226):</h3>
Along with Ravi I started by downloading the Makefile and the .c file on the VM, and added structs and definitions looking up in SDM for different capability region, added remaining msrs for each capability and also report_capability. For testing the code, i performed "make" command, to make the module, and inserted the module using insmod (using .ko file created) in kernel, and tracking the "dmesg". Initially there was a permission error, which we resolved using "sudo dmesg" command. I then created the git repo for the assignment, and i along with Ravi started pushing our code to the repository.<br>

<h3>Steps followed:</h3>
1. Retrieve the starter .c file and Mekefile from canvas. <br>
2. Add the remaining code sections to the file.(struct, definitions and vm features)<br>
