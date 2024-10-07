# powercanon
This Python script is designed to send a UDP payload to a specified target, commonly used to test the response of memcached servers. It allows users to define the target IP, port, the number of payloads (power), and the duration for which the script will run. The script is useful for network testing, including security evaluations and server performance monitoring. It sends the "stats" command by default but can be modified to send other payloads if needed.

Features:

Customizable target IP, port, payload power, and duration.

Simple and efficient UDP payload delivery.

Error handling for invalid inputs and connection issues.


Usage:

python3 memcached_payload.py