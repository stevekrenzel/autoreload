Autoreload is a simple python script to watch a directory for changed files
and restarts a process when the change is detected.

To use autoreload:

1. Make sure the script is executable by running `chmod +x autoreload`
2. Run `./autoreload <command to run and reload>`

For instance, I run `./autoreload python main.py`. This first runs
`python main.py`, then watches the current working directory and all
subdirectories for changes. If any changes are detected, then the
process is killed, and started all over again.


'''
Use  in conjunction w nohup on ubuntu server to kill PID of stale runserver process, and restart server for updated live deployment
'''
