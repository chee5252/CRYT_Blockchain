----
# Welcome to CRYT! #

----
## What is CRYT? ##
CRYT is a Blockchain ecosystem to make the world a better place.

----
## Get it! ##

  - *dependencies*:
    - *general* - Java 8
    - *Ubuntu* - `http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html`
    - *Debian* - `http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html`
    - *FreeBSD* - `pkg install openjdk8`

----
## Run it! ##

  - Double on:
  - Unix: `./start.sh`
  - Window: `run.bat`

  - wait for the JavaFX wallet window to open
  - on platforms without JavaFX, open http://localhost:11112/ in a browser

----
## Compile it! ##

  - if necessary with: `./compile.sh`
  - you need jdk-8 as well

----
## Troubleshooting the NRS (CRYT Reference Software) ##

  - How to Stop the NRS Server?
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report @ dev@crytrex.com

  - Permissions Denied?
    - no spaces and only latin characters in the path to the CRYT installation directory
    - known jetty issue

----
## Setting up Node and Help Network ##

  - Ubuntu 18:04
    - `apt install default-jdk`
    - `apt install openjdk-11-jdk-headless`
    - `git clone https://github.com/CryTrExcom/CRYT_Blockchain.git`
    - `sudo apt update`
    - `sudo ufw allow 11111`
    - `sudo ufw allow 11112`
    - `cd CRYT_Blockchain`
    - `screen`
    - `sh ./compile.sh`
    - `sh ./run.sh`
    - `CTRL+A+D`

----
## Further Reading ##

  - in this repository:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    - In the doc folder
    - Official Website: https://cryt.crytrex.com
    - Click Wiki on this repository for more info.

----

## License
* This program is distributed under the terms of the Jelurida Public License version 1.1 for the Ardor Public Blockchain Platform.
