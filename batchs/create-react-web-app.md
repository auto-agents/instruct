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

*/
```

## instructions

`/a c`

`/cd {{BASE_DIR}}/tmp/webapp`

- list available skills

- code a new web application using react and the best modern frontend and backend frameworks in the folder: `{{BASE_DIR}}/tmp/webapp`.
