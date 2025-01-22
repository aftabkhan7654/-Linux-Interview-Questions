🚀Linux-Interview-Questions

1. How can you run a shell script in the background in Linux?
Solution:
     To run a shell script in the background in Linux, you can use the following methods:
     1. Appending an Ampersand (&)
      - Run the script with & at the end of the command to run it in the background.
        Command : ./script.sh &
     2. Using nohup
      - The nohup command allows the script to keep running even if the terminal is closed.
        command : nohup ./script.sh &
  Verifying the Script is Running
       Command : jobs

