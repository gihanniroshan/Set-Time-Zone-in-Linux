# Set-Time-Zone-in-Linux
Set the time zone in Linux using Terminal/ Command Line - `timedatectl`


1. List available Time Zones
```
timedatectl list-timezones
```
```
timedatectl list-timezones | grep Colombo
```

2. Set the Time Zone
```
sudo timedatectl set-timezone <your_time_zone>
```
3. Verify the Time Zone
```
timedatectl
```
