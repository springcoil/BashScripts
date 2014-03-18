==
Some bash scripts
===

After setting up a VirtualBox with Ubuntu 12.04 LTS
 
Type 
sudo apt-get -y install git
And 
chmod u+x python.sh 
For each of the files here.
Run the ubuntu.sh file first. 
Then after that finishes run
pip install virtualenv 
pip install virtualenvwrapper



Add three lines to your shell startup file (.bashrc, .profile, etc.) to set the location where the virtual environments should live, the location of your development project directories, and the location of the script installed with this package:

export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
source /usr/local/bin/virtualenvwrapper.sh

After editing it, reload the startup file (e.g., run source ~/.bashrc).
Alternatively you could edit the shell files to suit your actual profile. It looks like the script I downloaded was designed for MacOSX hence I had some trouble originally. 

Then I just ran ./python.sh and the other one for ./hadoop_ecosystem.sh

I'm more a fan personally of using VirtualBox than Vagrant. But I understand the arguments made for Vagrant...

