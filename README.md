# webpentest
This is a webpage pentest tool for testing web server vulnerabilities.




## Author

@14mb1v45h

# Installation
    $ apt update && apt update -y
    $ apt install git -y
    $ apt install python -y
    $ pip2 install requests
    $ pip install requests
    $ git clone https://github.com/14mb1v45h/cyberspace063.git
    $ cd cyberspace063
    $ git pull
    $ python whitepentest.py
    
    
# Note

⚠️Only tests websites with Webpentest vulnerability(Accepts unauthenticated requests)⚠️ 


# Webpentest Testing Script

The Webpentest Testing Script is a Python script designed to assess the vulnerability of a web server to Webpentest (Web Distributed Authoring and Versioning) attacks. Webpentest is an extension to the HTTP protocol that enables collaborative editing and remote file management on web servers.

The script is divided into several functions that perform different actions related to Webpentest testing. Here's an overview of the functionalities provided:

<i>🪲Test URL for Webpentest vulnerability: This function checks a specific URL for the presence of Webpentest vulnerability by attempting to upload a test file to the server. If the upload is successful, the URL is considered vulnerable.</i>

<i>🪲Test multiple URLs from a file: This function reads a file containing a list of URLs and tests each URL for Webpentest vulnerability using the previous function. It generates a report indicating which URLs are vulnerable.</i>

<i>🪲List Directory: This function retrieves and displays the directory listing of a specified URL using the PROPFIND method. It shows the name, size, and last modified date of each file and subdirectory within the directory.</i>

<i>🪲Change Directory: This function allows changing the current working directory by appending a directory name to the base URL.</i>

<i>🪲Upload File: This function uploads a local file to a specified URL using the PUT method. It reports whether the upload was successful or not.</i>

<i>🪲Download File: This function downloads a file from a specified URL using the GET method and saves it to the local system.</i>

<i>🪲Print Working Directory: This function retrieves and displays the current working directory (URL) using the PROPFIND method.</i>

<i>🪲Edit File: This function allows editing a file on the server by retrieving its content, opening it in the Nano text editor, modifying the content, and saving the changes back to the server.</i>

<i>🪲Delete File: This function deletes a file from the server using the DELETE method.</i>

<i>🪲Delete Directory: This function deletes a directory and its contents from the server using the DELETE method.</i>

<i>🪲Copy File: This function copies a file from a source path to a destination path on the server using the COPY method.</i>

<i>🪲Get Server Version: This function retrieves and displays the server version, supported methods, and additional server details using the OPTIONS method.</i>

🪲Delete All Files: This function deletes all files within a specified directory on the server.</i>

<i>🪲Delete Specific Files: This function deletes a list of specific files (separated by commas) on the server.</i>

The script provides a menu-based interface to interact with these functionalities, allowing users to choose the desired action and provide the necessary inputs. It also includes error handling and informative messages to guide the user throughout the process.

To run the script, ensure that the required dependencies (requests, subprocess, xml.etree.ElementTree) are installed. The script can be executed from the command line or integrated into other projects for automated web server testing.

Please note that this script should only be used for ethical purposes with proper authorization. Unauthorized testing of web servers can be illegal and may lead to severe consequences.



