The included script allows for a standard installation of the License Manager (synd) as a service under Linux (eg, RedHat/Fedora/CentOS).

1. Copy the file to /etc/init.d and edit the SYNDIR line to include the correct path to the base Synergy/DE directory.  

2. Make the script file executable using "chmod a+x synd".

3. Run "chkconfig synd --add" to add the service to the system runlevel directories for automatic start/stop when the system is brought up or down.

Note: This will also enable the use of the "service" command method of starting/stopping/restarting the license manager. i.e., service synd stop

