# Thursday Morning Challenge (Roles)

Create a playbook that runs against the planetexpress hosts (excluding farnsworth) that does the following:

- Uses pre_tasks to create a ~/nginx directory, and calls on a handler if this made a change (debug)
- Uses roles (1) that 
    - copies a file into the ~/nginx directory
    - installs the apt package nginx
    - calls on a handler if nginx was installed (debug) 
- Uses tasks (1) to perfrom an "ls" command on the home directory
- Uses post_tasks (1) to remove the ~/nginx directory


## Rocket Scientist
- Make your role accept a variable that allows you to change the state of nginx between present or absent
- Register and debug the results of your "ls" task
- Perform same actions on farnsworth (but some things will have to change!!!)

