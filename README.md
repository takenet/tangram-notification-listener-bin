# Binaries of  tangram-notification-listener

The repository includes the binaries from tangram-notification-listener.
**tangram-notification-listener** <sup id="TNLPos">[[1]](#TNL)</sup> is a console application that listen TANGRAM notification requests at 8181 port and outputs both the request and the response.

> **Note**: You need Java Runtime Environment (JRE) to run the application. You can download Java [here](https://www.java.com/download/).

The purpose of this application is to test the TANGRAM flows quickly. The application outputs raw request and response datas. Along with the scripts presents in this repository, partners can test the asynchronous behavior of TANGRAM.

You can find the binaries of tangram-notification-listener here. Click on **Download ZIP** button or directly download the latest version [here](https://github.com/takenet/tangram-notification-listener-bin/archive/master.zip).

On your computer, unzip the archive and execute tangram-notification-listener.exe by double clicking. On Unix system, using a terminal console go to the application path and execute the following command:

```
java -jar tangram-notification-listener.jar
```

The application will start and wait for notification requests. Note that the application needs permission the write log files at its own folder. The application will create a subfolder called *log*.

If you like to modify some behavior of the tangram-notifier-listener, you can get the application sources here:

> [tangram-notification-listener](https://github.com/takenet/tangram-notification-listener)

# References
<a name="TNL">1</a>. [TANGRAM notification listener application](https://github.com/takenet/tangram-notification-listener). [↩](#TNLPos)
