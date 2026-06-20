# networking

## commands

### check network speed
```sh
networkquality
```

### check network info
```sh
ifconfig
```

### check wifi info
```sh
networksetup -getinfo wi-fi
```

### get IPs
```sh
# device IP - ipv4
curl -s https://api.ipify.org && echo

# device IP - ipv6
curl -s https://api6.ipify.org && echo

# device IP - internal
ifconfig | grep "inet " | grep -v 127.0.0.1 | awk '{print $2}'

# router IP
networksetup -getinfo wi-fi | grep "Router:" | grep -v "IPv6" | awk '{print $2}'
```

## apps

- **[proxyman](https://proxyman.com)** is a free app to capture, decrypt, and mock HTTP requests/responses with powerful debugging tools.

- **[nmap](https://nmap.org)** is a free and open-source network scanner. nmap is used to discover hosts, ports and services on a computer network by sending packets and analyzing the responses.
