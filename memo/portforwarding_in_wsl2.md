## In powershell
> netsh interface portproxy add v4tov4 listenport=8000 listenaddress=0.0.0.0 connectport=8000 connectaddress=172.29.145.225

## How to get connectaddress
In ubuntu,
> hostname -I
