/etc/sudoers.d/claudedev 

claudedev ALL=(root) /usr/bin/apt update, /usr/bin/apt install *, /usr/bin/apt-get install *, /usr/bin/add-apt-repository *
claudedev ALL=(root) /usr/bin/systemctl restart *, /usr/bin/systemctl status *, /usr/bin/systemctl start *, /usr/bin/systemctl stop *
