# BackupCiscoConfig
A script to backup a set of cisco devices

<b>Pre-Request:</b><br>
sshpass<br>
a tftp server to save backups<br>
a file that contains IPs<br>
username and password to access devices (RO is enough)<br><br>
<b>Installation:</b><br>
apt install sshpass<br>
git clone https://github.com/alirezaunix/BackupCiscoConfig.git<br>
cd BackupCiscoConfig<br>
chmod +x BackupCiscoConfig<br>
./BackupCiscoConfig<br>
