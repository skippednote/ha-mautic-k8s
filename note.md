k expose pod mysql --port 3306 --dry-run=client -o yaml
k expose deploy redis --port=6379
k create secret generic digitalocean-dns --from-literal="" 
 <https://cert-manager.io/docs/configuration/acme/dns01/digitalocean/>
