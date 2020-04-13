# something_awesome
the main idea is to send evil file along with normal file as one single file to the victim, 
but when they open the final file that’s when the evil trojan file starts its magic.
This Trojan Factory is designed to be as generic as possible, it can be used to embed evil files within any normal file("final-file"), it does this using an Autoit download-and-execute script, so basically it takes 2 URLs:

1. One for a normal file (can be a pdf, mp3. doc, exe ...etc)&semi;
2. And an evil file (backdoor, keylogger ...etc). The result is one exe that when executed, presents the normal file to the user and runs the evil file in the background.
