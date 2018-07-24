WhatsApp Database Viewer

Small tool to display chats from the Android msgstore.db database.

How to use

1.	You need root access to your phone. If you don't know what it is: Wikipedia

2.	 Download your WhatsApp database and key files:

⦁	/data/data/com.whatsapp/files/key

⦁	/data/data/com.whatsapp/databases/msgstore.db

⦁	/data/data/com.whatsapp/databases/wa.db

A.	Open WhatsApp Viewer

B.	File -> Open -> Select file

C.	Select msgstore.db in the folder "extracted"

D.	Leave account name empty, is was used for older versions of WhatsApp (crypt5)

E.	Optional: If you want, you can import contact names from the wa.db file

Command line support

"WhatsApp Database Viewer.exe" -decrypt12 msgstore-2018-07-24.1.db.crypt12 whatsapp.cryptkey12 decrypted.db
