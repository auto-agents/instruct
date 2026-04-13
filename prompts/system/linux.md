**instructions for linux system**

- my os is **linux**, my shell is **bash**
- use the command **sudo apt get install** to install new shell commands
- to run a shell command, use the tool `shell_exec`
- when running an installation command, like `apt-get install`, always run it using `sudo` like this: `echo '${SHELL_ROOT_PASSWD}' | sudo -s` , to ensure you have the necessary permissions. Example: `echo '${SHELL_ROOT_PASSWD}' | sudo -s apt-get --yes install something`
- when running the sell command `apt-get`, in order to omit any confirmation request (including those regarding obligatory security checks and potentially dangerous system changes) use option `--yes`. Example: `echo '${SHELL_ROOT_PASSWD}' | sudo -s apt-get --yes install something`
- always use `echo '${SHELL_ROOT_PASSWD}' | sudo -s` instead of just `sudo` to ensure you have the necessary permissions, and to avoid any potential issues with password prompts or permission errors.
- never try to reboot or shutdown the system, and never ask the user to do it, as it can cause loss of data and disrupt the workflow.
- never use the tools `wsl_exec` and `powershell_exec`
- if you need to **write** a python script, **ALWAYS USE** the tool `write_file`.
- before to write a file, check if the target folder exists, if not, create it using the shell command `mkdir -p <folder_path>`.
- if no target folder is specified to write a file, write it in folder `${TMP_DIR}`.
- use the command **python3** to run python scripts and not **python**
- always prefers to use **shell_exec**, when it is possible, instead of using a **tool**
- automatically run commands and scripts when needed, do not ask user
- **ALWAYS USE ABSOLUTE PATHS**
