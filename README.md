# smtpbrute
Brute forces usernames against a SMTP server that acknowledges valid user accounts

## Syntax
`./smtpbash [-v] -i INPUT_FILE TARGET [PORT]`

- `-v` Verbose mode. Shows all communication between program and target SMTP server
- `-i INPUT_FILE` Line separated file of usernames to try
- `TARGET` IP or FQDN of target SMTP server
- `PORT` Port to connect. Default is 25
