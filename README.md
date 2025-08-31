# Arnold Atchoe
# INITIAL STREAMING DATA PROJECT: BUZZLINE MESSAGES.

# buzzline-01-arnold


This project introduces streaming data. 
The Python language includes generators - this feature is used to generate some streaming buzzline messages. 
As the code runs and produces buzzline messages, it will continuously update the log file. 
Consumer is used to monitor the log file and alert us when a special message is detected. 

This course made used of **Python 3.13.5**. 

**Setup is critical.** Before project was initialized, I ensured that the needed software,dependencies and other resources are setup correctly. IDE used for project was VS Code.Libraries required for this project is listed in **requirments.txt.** file.

### Note:

1. Ensure that virtual environment is always activated for each step of the project.
2. Make sure dependencies are installed and imported before using them.

## Task 1. Initialize a Project

Once my machine was ready, I copied the template repository https://github.com/denisecase/buzzline-01-case, into my own GitHub account  to created a personal version of the project to run and explore. Project was cloned onto my machine to worked on. At certain points of the project, **git pull** and **git push** was used to keep the local project folder and that in my GitHub account in sync.

This will get your project stored safely in the cloud - and ready for work on your machine. 

## Task 2. Generate Streaming Data (Terminal 1)
A new producer module was created to customize the original producer module.

Changes made in the new producer module include;
1. Changing the message interval.
2. Customizing the buzzline message generated.

Next I generated some streaming data. 

In VS Code, I opened a terminal in my root project folder and ran the producer.
 
Windows PowerShell:

```shell
py -m producers.basic_producer_arnold
```

## Task 3. Monitor an Active Log File (Terminal 2)

A common streaming task is monitoring a log file as it is being written. 
This project has a consumer that reads and processes our own log file as log messages arrive. 

In VS Code, I opened a NEW terminal in my root project folder. 
Used the commands below to ran the file as a module. 

Windows:
```shell
py -m consumers.basic_consumer_arnold
```

### Note:
Both producer and consumer module can be terminated using Ctrl+C in the terminal where they are being executed.

## Save Space
To save disk space, you can delete the .venv folder when not actively working on this project.
We can always recreate it, activate it, and reinstall the necessary packages later. 
Managing Python virtual environments is a necessary and valuable skill. 
We will get a good amount of practice. 

## License
This project is licensed under the MIT License as an example project. 
You are encouraged to fork, copy, explore, and modify the code as you like. 
See the [LICENSE](LICENSE.txt) file for more.
