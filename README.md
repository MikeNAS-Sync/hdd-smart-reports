# hdd-smart-reports

...
sudo smartctl -x /dev/sdX > SERIAL-smart-before.txt
sudo badblocks -b 4096 -c 1024 -wsv -t 0 /dev/sdX
sudo smartctl -x /dev/sdX > SERIAL-smart-after.txt
...
