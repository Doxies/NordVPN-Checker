NordChecker
NordChecker is an advanced version of NordChecker and also influenced by it. It is a seleium driven application used to bypass almost all the security checks nordvpn is using to block bots



Requirements
Chromium WebDriver
Python 3.x
Dependencies
proxybroker
colorama
argparse
selenium
psutil
How to Use
Clone the repository git clone 

Change the directory cd nordchecker

Get the requirements and add the Chrome Driver to your PATH variable

Install the dependencies pip install --user -U -r requirements.txt

Run the script python app.py --file [filename] --separator [username - password separator]

For example,

FileName: lists.txt
Username Password Separator: :
 $ python app.py --file lists.txt --separator :
Help
usage: app.py [-h] --file PATH --separator SEPARATOR [--workers]

A damn easy nordvpn account validator

optional arguments:
  -h, --help            show this help message and exit
  --file PATH           The file name containing all username password
  --separator SEPARATOR
                        Username and password separator
  --workers             Set the number of workers. default: 3

Contribution
Rules
Pull requests must be made from another branch, not the master branch
Add valid commit message
Describe the change in pull request
Scope
Adding bypass of NULL response from https://ucp.nordvpn.com/login/
Getting valid proxies everytime
Adding some troubleshooting to the readme
