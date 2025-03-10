# Day 4 Task: Basic Linux Shell Scripting for DevOps Engineers.

 ## What is Kernel

 The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system.
 
 ## What is Shell

 A shell is special user program which provide an interface to user to use operating system services. Shell accept human readable commands from user and convert them into something which kernel can understand. It is a command language interpreter that execute commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or start the terminal.
 
 ## What is Linux Shell Scripting?

 A shell script is a computer program designed to be run by a linux shell, a command-line interpreter. The various dialects of shell scripts are considered to be scripting languages. Typical operations performed by shell scripts include file manipulation, program execution, and printing text.

 **Tasks**

 - Explain in your own words and examples, what is Shell Scripting for DevOps.
 - Shell Scripting used in DevOps to automate things so that human interfare and efforts can be minimized.
 - What is `#!/bin/bash?` can we write `#!/bin/sh` as well?
 - We can use use both shebangs as both are pointing to different shells.
 - Write a Shell Script which prints `I will complete #90DaysOofDevOps challenge`
 - #!/bin/Bash
   echo "\`I will complete #90DaysOofDevOps challenge\`";
 - Write a Shell Script to take user input, input from arguments and print the variables.
 - #!/bin/Bash
   echo -n "Enter your name:"
   read  name
   echo "Your name is $name and age is $1"
 - Write an Example of If else in Shell Scripting by comparing 2 numbers
   #!/bin/Bash
   num1=55
   num2=58

   if [ $num1 -gt $num2 ] 
   then
       echo "$num1 is greater than $num2";
   elif [ $num1 -eq $num2 ] 
   then
       echo "$num1 is equal to $num2"
   else 
       echo "$num2 is greater to $num1"
   fi
 Was it difficult?
 
 - Post about it on LinkedIn and Let me know :)

 Article Reference: [Click here to read basic Linux Shell Scripting](https://devopscube.com/linux-shell-scripting-for-devops/)

 YouTube Vedio: [EASIEST Shell Scripting Tutorial for DevOps Engineers](https://www.youtube.com/watch?v=_-D6gkRj7xc&list=PLlfy9GnSVerQr-Se9JRE_tZJk3OUoHCkh&index=3)
