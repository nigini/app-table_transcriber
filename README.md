PyBossa demo application Table Transcriber. It aims to get and present some old tables collaborators can help to transcribe. 

This application works in 3 steps:

*  static/downloadPDF2PNG.sh: it will help you to download old books and convert its pages in images to be presented at PyBossa Tasks.
*  tabletranscriber.py: for creating the application in PyBossa, and fill it with tasks.
*  tabletranscriber.html: the view for every task. It will depend on more files... Look at the next step.

Testing the application:

*  Create an account in PyBossa
*  Copy under your account your API-KEY
*  Run python tabletranscriber.py -u http://0.0.0.0:5000 -k API-KEY (change URL server as needed)
*  Open with your browser tabletranscriber.html and see the tasks!
