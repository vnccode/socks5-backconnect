# Socks5-backconnect
Socks5 backconnect server . Expose a local socks5 server behind a NAT or firewall to the internet. 


- VPS Linux   

https://github.com/fatedier/frp/releases

./frps &

- Windows

Edit frps.ini

Change VPS IP

Run socks5.exe     ( socks5 server port 1080 )

Run start.bat

This will create a socks-proxy on VPS IP port 32000
