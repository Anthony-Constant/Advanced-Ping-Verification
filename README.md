<h1>Introduction</h1>
<p>This is an advanced Ping verification script created in Python by Anthony Constant (AC). The purpose of this script is to automate the process of pinging a maximum number of devices inside a network and return whether the network status is successful or unsuccessful. The script uses the write method to create/open/write the status to a file called ping_logs.txt.</p>
<h2>How to Use</h2>
<p>To use this script, you need to specify the maximum number of target IP addresses in the range method. The script will then ping each IP address in the range and return whether the ping was successful or unsuccessful. The status of each ping will be written to the ping_logs.txt file.</p>
<h2>Requirements</h2>
<p>This script requires Python 3 to be installed on your machine.</p>
<h2>How It Works</h2>
<p>The script uses the os module to execute the Ping command in the command prompt. It then captures the output of the command to determine whether the Ping was successful or not. The status of each Ping is then written to the ping_logs.txt file using the write method.</p>
<h2>References</h2>
<p>If you would like to learn more about Ping and Traceroute commands, you can refer to the following link: <a href="https://www.cisco.com/c/en/us/support/docs/ios-nx-os-software/ios-software-releases-121-mainline/12778-ping-traceroute.html">https://www.cisco.com/c/en/us/support/docs/ios-nx-os-software/ios-software-releases-121-mainline/12778-ping-traceroute.html</a></p>
<h2>Credits</h2>
<p>This script was created by Anthony Constant (AC). If you have any questions or suggestions, you can contact him at <a href="anthonyconstant.co.uk">anthonyconstant.co.uk</a></p>
<h2>License</h2>
<p>This script is released under the MIT License. See the LICENSE file for more details.</p>
