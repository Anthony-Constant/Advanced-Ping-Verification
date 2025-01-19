# Advanced Ping Verification Script

## Introduction

This is an advanced Ping verification script created in Python by Anthony Constant (AC). The purpose of this script is to automate the process of pinging a maximum number of devices inside a network and return whether the network status is successful or unsuccessful. The script uses the `write` method to create/open/write the status to a file called `ping_logs.txt`.

## How to Use

To use this script, you need to specify the maximum number of target IP addresses in the `range` method. The script will then ping each IP address in the range and return whether the ping was successful or unsuccessful. The status of each ping will be written to the `ping_logs.txt` file.

## Requirements

This script requires Python 3 to be installed on your machine.

## How It Works

The script uses the `os` module to execute the Ping command in the command prompt. It then captures the output of the command to determine whether the Ping was successful or not. The status of each Ping is then written to the `ping_logs.txt` file using the `write` method.

## References

If you would like to learn more about Ping and Traceroute commands, you can refer to the following link: [Ping and Traceroute - Cisco](https://www.cisco.com/c/en/us/support/docs/ios-nx-os-software/ios-software-releases-121-mainline/12778-ping-traceroute.html)

## Demo

https://youtu.be/5r-wPG667QQ

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

This script was created by [Anthony Constant](https://anthonyconstant.co.uk/). 

## Support My Work

If you like this repository or have used any of the code, please consider showing your support:

- Give it a star ⭐️ to acknowledge its value.
- You can also support me by [buying me a coffee ☕️](https://ko-fi.com/W7W144CAO).

