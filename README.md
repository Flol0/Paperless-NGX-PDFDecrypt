# Paperless-NGX-PDFDecrypt

## Import encrypted mails into Paperless-NGX by decrypting them.



I created this script to automatically decrypt encrypted payslips from my employer and then import them into Paperless-NGX.

I have maintained all my variables in **docker-compose.env**.

In the **docker-compose.override.yaml** the directory **/opt/paperless/bin** is mounted in the directory of the same name in the container.

Both the script used for decryption and the password list, which I use to theoretically store several passwords, are located here.

An attempt is therefore also made to decrypt a document with possibly incorrect passwords. I don't really use it for anything else so far, so it was the easiest way to use different passwords.
