Task 1 - Scan Your Local Network for Open Ports

Objective:-To discover devices on the local network and identify open TCP ports using Nmap.

Tool Used:-Nmap 7.99

Network Range:-10.53.170.0/24

Scan Command:-```bash nmap -sS 10.53.170.0/24
```

Scan Results:

1)Device 1

IP Address: 10.53.170.200

Open Port:
- 53/tcp (DNS)

2)Device 2

IP Address: 10.53.170.6

Open Ports:
- 135/tcp (MSRPC)
- 139/tcp (NetBIOS Session Service)
- 445/tcp (Microsoft-DS)
- 7070/tcp (RealServer)

Security Risks:-

1)Open ports may allow network services to be accessed.
2)Unnecessary open ports can increase security risks.
3)Firewalls should be used to restrict unwanted access.

Conclusion:-

The local network scan successfully identified active devices and their open TCP ports. This demonstrates how Nmap can be used for basic network reconnaissance.