# SMTP Program

A sample SMTP client-server program made for our lab

## How to run

1. Make sure the current working directory is this folder

2. Open three to five windows: 1 for SMTP server, 1 for POP3 server and the rest for each client

3. Compile the files using the following commands:

    `gcc Source\ Code/imapserver.c -o Outputs/imap`

    `gcc Source\ Code/smtpmail.c -o Outputs/smtp`

    `gcc Source\ Code/mailclient.c -o Outputs/client`

4. Run IMAP server using: ./Outputs/imap \<port\_number\>

5. Run SMTP server using: ./Outputs/smtp \<port\_number\>

6. Run client program using: ./Outputs/client \<SMTP\_port\_number\> \<IMAP\_port\_number\>
