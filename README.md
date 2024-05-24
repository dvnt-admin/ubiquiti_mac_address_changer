# ubiquiti_mac_address_changer
command that changes the max address of nanostation m5

```
echo "ifconfig ath0 down; ifconfig ath0 hw ether AC:D6:18:E7:B6:85; ifconfig ath0 up" > /etc/persistent/rc.poststart; chmod +x /etc/persistent/rc.poststart; cfgmtd -w -p /etc/; reboot
```
