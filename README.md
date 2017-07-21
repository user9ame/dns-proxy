Python DNS proxy server with blacklist support using [dnslib](https://pypi.python.org/pypi/dnslib) library

# To Use on Linux
Run the `dns_proxy_server.py` script:
```bash
sudo python3 dns_proxy_server.py
```

Change default nameserver in the `/etc/resolv.conf` file 
by adding the following line to the top of the name server list:

`namesever 127.0.0.1`
