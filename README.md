# Bidirectional Sync

This project is designed to provide a bidirectional sync between your local and a single host (web or ssh). The sync is achieved using the rclone command-line tool.

## Requirements

- rclone installed on both the machine that will be running the sync 
- rclone configured to connect to the host

## Setup

1. Clone this repository onto your local machine.
2. On the local machine, create a cron job to run the `main.py` script at regular intervals. 
    - For example, to run the script every 5 minutes, add the following line to your crontab:
## Usage
Once the setup is complete, any changes made to files on the local machine will be synced to the host, and any changes made to files on the host will be synced to the local machine.