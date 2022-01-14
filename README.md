# traefik-pebble
contains all config for traefik and pebble
1. run portainer to spin up poetainer dont associate portainer with traefik
2. run pebble server / keep that cert folder also traefik uses the minica.pem to communicate with pebble server
3. run traefik and configure hosts file accordingly
4. run authelia
5. then run any services
6. my hosts be like
192.168.1.10		minimal.home nginx.minimal.home traefik.minimal.home auth.minimal.home
# ALL WILL BE CERTIFIED EXCEPT PORTAINER BY PEBBLE 