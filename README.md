Remote Host Information Script

This script is a simple Python program that retrieves and displays the IP address of a specified remote host using the socket library.
Features

    Fetches the IP address of the remote host rmit.edu.au.
    Displays the host name and its resolved IP address.
    Includes error handling to notify the user if the host cannot be accessed.

How to Use

    Prerequisites:
    Ensure Python is installed on your machine (Python 3.x recommended).

    Run the Script:
    Execute the script by running the following command in your terminal:

        python script_name.py



Expected Output:
The script will output the remote host name and its IP address.
    Example:

    Remote host name: rmit.edu.au
    IP Address: 203.10.91.32

    Error Handling:
    If there’s an issue accessing the host, the script will output an error message with details.

Notes

    The script can be modified to query different hostnames by updating the remote_host variable.
    Useful for testing DNS resolution or checking connectivity.
