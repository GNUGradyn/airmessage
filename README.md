# airmessage
Send messages over airdrop, NFC, or bluetooth

Airmessage is a simple script that allows you to send messages over airdrop, nfc, bluetooth, and any other similar method by creating a custom link that opens a javascript alert with your message.

Known bugs:
exit() failes due to the fact that the page was opened by a forum, and exit() can only be called by the script that opened the window. This causes the message to re-appear if the user does not manually close the tab
