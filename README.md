# Spammer-Email
[![Python 2.6|2.7](https://img.shields.io/badge/python-2.6|2.7-yellow.svg)](https://www.python.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://raw.githubusercontent.com/p4kl0nc4t/Spammer-Email/master/LICENSE)

Spams an email inbox by sending email from an SMTP server repeatedly. This script is working under Python 2.7.

## Usage
```
usage: Spammer-Email [-h] [--ssl] [--username USERNAME] [--password PASSWORD]
            to subject body from host port

Spammer (Email) is a tool used to spam an email address by sending an email
repeatedly using an SMTP server.

positional arguments:
  to                   the email address to spam
  subject              body of the email to send
  body                 body of the email to send
  from                 mail from. Not all SMTP server accepts this, prefer
                       using provided email address
  host                 the SMTP server host
  port                 the SMTP server port

optional arguments:
  -h, --help           show this help message and exit
  --ssl                the SMTP server requires SSL
  --username USERNAME  username for SMTP server auth
  --password PASSWORD  password for SMTP server auth
```
