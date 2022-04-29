### Basic Linux Commands.
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/1200px-Tux.svg.png" alt="Linux image" height=100 width=100>
Hello, everyone, before diving into the concepts of Docker and Kubernetes, it is very important that we know some basic Linux commands that we will be using throughout our journey.<br>

### Commands and their meaning.<br><hr>

1. $ls = list command, i.e gives list of information about the files and directories in the current directory.
2. $ls -ltr = gives a little more information about that.
3. $mkdir = create a directory.
4. $cd = changing the directory.
5. $cd .. = go to the previous directory.
6. $touch = create a file in a directory.
7. $vi = to add content inside the above created file , press 'I' to get in the insert mode and when content addition is done , press 'esc' and type ':x' or ':wq!' and enter.
8. $cat = to view what's inside the file.
9. $clear = to clear the screen whatever is present on it.
10. $cp = copy the file and also add the directory to where you want to copy it(ex: cp names.txt hello , where hello is a directory) hence a copy will be present at the original location as well.
11. $mv = same as cp command but here file will be completely moved , i.e no copy is remained in the original directory.
12. $chmod = changing the permission of the file(ex:rwxr-x--x where 1st three will be a set - read , write and execute.Where 4=read , 2=write and 1=execute, so $chmod 400 xyz will have the file permission as r----------)
13. $env = displays all the environment variables.
14. $export demo=hello = exporting the variable(i.e if we type 'echo $demo' hello would be displayed)
15. $kill = to kill a specific process.
16. $du = disk utility command(disk occupied by the files and directories) but its not in the human readable format , hence use the command { $du -h } for human readable format.
 <hr>

<h3>So these are some of the very basic linux command required to get started , learn while doing.</h3>
