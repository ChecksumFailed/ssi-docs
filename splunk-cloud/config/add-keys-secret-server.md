[title]: # (Adding keys to Secret Server Config file)
[tags]: # (introduction)
[priority]: # (104)
# Adding keys to Secret Server Config file

We must create a folder and file to save the Syslogs on the computer where
Secret Server is installed.

**To add keys to the Secret Server config file:**

1.  On the computer where Secret Server is installed, create a folder and a file
    within the folder where you want to save the **Syslogs.**

2.  On the computer where Secret Server is installed, go to **inetpub** \>
    **wwwroot** \> **SecretServer** \> **web-appSettings.config** file.  
    

    ![](images/afc3d0f272592177cf81a1b54da5278a.png)

3.  Open the **web-appSettings.config** file in Notepad.

    ![](images/2f2fb8b1c57945863452548460fbcf74.png)

4.  Add the keys as shown below.

    ![](images/736a6b5adf4fb351b3cd8db45debcab7.png)

    Where “Path of the Log file” is the path of Syslog file that is created in
    [Step 1](#Adding_Keys_Step_01). The keys are now added to the Secret Server
    config file.