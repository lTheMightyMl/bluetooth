# bluetooth
Code for bluetooth data transfer in Python on Raspberry Pi

Run the following command on Raspberry Pi to install the required packages:

```sh b.sh```

`scan.py` scans for bluetooth devices and prints them

`server.py` sets up a server with a hard-coded UUID and waits for the client, then receives everything until the client disconnects

`client.py` looks for the server with the hard-coded UUID and sends data read from STDIN
