# create react web app

## about batch syntax

```js
/*
batch syntax:

replace vars:
	${env_var}		value from environment variables
	{{var}}				value from context variables

lines starting with '-' are ai agent prompt, until next other directive line
- ai prompt

lines starting with '/' are cli commands, until the end of the line
/cli_command

\```
texts blocks for any syntax are ignored
\```

\```js
javascript syntax texts blocks are used to write code, and the content will be used as code to execute
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

- code a new web application in the folder: `{{BASE_DIR}}/tmp/webapp`, that uses react and the best modern frontend and backend frameworks

- code a new web application in the folder: `E:\tmp\webapp`, that uses react and the best modern frontend and backend frameworks. directly code the files do not prepare a plan.

- code a new web application in the folder: `/mnt/e/tmp/webapp`, that uses react and the best modern frontend and backend frameworks. directly code the files do not prepare a plan.

- apply your plan , make the folder structure, install the librairies and the frameworks, write the files
