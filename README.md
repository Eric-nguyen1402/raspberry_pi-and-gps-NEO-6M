# raspberry_pi-and-gps-NEO-6M
First, you need to get permission from raspberry to use /dev/ttyAMA0 if have an error Permission Deny /dev/ttyAMA0
- sudo systemctl stop serial-getty@ttyS0.service
- sudo systemctl disable serial-getty@ttyS0.service
- sudo systemctl enable serial-getty@ttyAMA0.service
- sudo cat /dev/ttyAMA0
