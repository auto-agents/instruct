# create react web app

## about batch syntax

```js
/*
batch syntax:

replace vars:
	{{cli_env_var}}

lines starting with '-' are ai agent prompt, until next other directive line
- ai prompt

lines starting with '/' are cli commands, until the end of the line
/cli_command

\```
texts blocks are ignored
\```

lines starting with # (titles) are ignored

free text should be ignored, it is only for human readability and comments

*/
```

## instructions

`/a c`
`/a mute`

`/cd {{BASE_DIR}}/tmp/webapp`

- list available skills

- **ALWAYS** use `;` to separate commands (eg. in powershell_exec or shell_exec command argument) and **NEVER** `&&`.

- code a new web application in the folder: `{{BASE_DIR}}/tmp/webapp`, that uses react and the best modern frontend and backend frameworks

- code a new web application in the folder: `E:\tmp\webapp`, that uses react and the best modern frontend and backend frameworks. directly code the files do not prepare a plan.

- code a new web application in the folder: `/mnt/e/tmp`, that uses react and the best modern frontend and backend frameworks. directly code the files do not prepare a plan.

- apply the plan
