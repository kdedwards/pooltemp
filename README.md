# pooltemp

Bash script to parse output from rtl_433 and update a DNS record. Uses the rtl_433 utility found here: <https://github.com/merbanan/rtl_433>

I wanted a lightweight and easy way to query the temperature of my pool when out and about. This script runs on a raspi with an SDR dongle attached. The script runs on a schedule in crontab and will update a configured DNS A record if the temperature is different.