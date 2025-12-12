# python-network-connection-input-project
python socket project for sending input to another device and processing locally
# Python Network Input Processing Project

## Project Idea
This project takes input from the user on the sender’s device.  
At the same time:
1. Sends the input to another device using socket network communication.
2. Processes the same input locally and shows output.

## Files
- sender.py → User input + sending + local processing  
- receiver.py → Receives message from sender  

## How It Works
1. Run receiver.py on Device 2  
2. Run sender.py on Device 1  
3. Enter a number → Receiver gets it → Sender processes it locally  

## Requirements
- Python 3.x  
- Both devices on same network (WiFi/Hotspot)

## Run Commands
```bash
python receiver.py
python sender.py
