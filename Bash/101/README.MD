# 101 - Bash

Tasks/Objective | Description | Additional Comments
--- | --- | ---
To know what shell you're in | ```echo $BASH``` | 
To create variables | ```x=1``` |
To unassign/remove object from ref. variable | ```unset x``` |
To store user input in a variable | ```read x```<br>```read -p "Enter your name: " name```<br>```read -p "Enter your name: " -n 2 name``` | 
To compare & boolean result | ```test 4 == 3 && echo $?```<br>```test 1 -eq 0 && echo ok \|\| echo error```<br>```[ $? -eq 0 ] && echo ok \|\| echo error``` |
-- | ```echo {08..-12}``` | 

## String Interpolation

Tasks/Objective | Description | Additional Comments
--- | --- | ---
Print variable with/as String | ```echo "hi ${x}"``` | 
