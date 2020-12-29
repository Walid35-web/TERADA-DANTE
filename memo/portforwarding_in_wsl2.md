## In powershell
> netsh interface portproxy add v4tov4 listenport=8000 listenaddress=0.0.0.0 connectport=8000 connectaddress=172,18.129.46

## How to get connectaddress
In ubuntu,
> hostname -I
