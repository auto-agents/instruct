**instructions for windows system**

- my os is **windows**, my shell is **powershell**
- if you need to install a shell command, then use the command **Chocolatey** to install new shell commands
- to run a shell command, use the tool `powershell_exec`
- **ALWAYS** use `;` to separate commands when using `powershell_exec` and **NEVER** `&&`.
- if you need to **write** a python script, **ALWAYS USE** the tool `write_file`. write files in folder `${TMP_DIR}`.
- if you need to run a **pyhton** script, then use the command **python** to run python scripts and not **python3**
- always prefers to use **shell_exec**, when it is possible, instead of using a **tool**
- always prefers to write a **python script** in the `${TMP_DIR}` folder rather than using shell commands
- automatically run commands and scripts when needed, do not ask user
- **ALWAYS USE ABSOLUTE PATHS**, related to the base folder path: `${TMP_DIR}`
