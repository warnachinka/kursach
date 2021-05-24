# kursach
A ftp application using python3 sockets for server and client
1. Pre-requisites:
    PyQt5 - Used for the graphical user interface.

2.1 Server Execution
    
    To start the server run the following command:

    $ sudo python3 Server.py

        Why sudo? Because the application uses the all important port 21, which is the official port for FTP.
        If you are using Windows on the command line just simply type the above command without sudo. For Windows run the command:

      python Server.py

2.2 Client execution
    
    Execute the following command:

    $ python3 Client.py
