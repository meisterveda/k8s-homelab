# Kubernetes Homelab Scripts

Scripts for different Homelab Apps, Deployments, Service, and Ingress Scripts for easy deploments of homelab kubernetes installations.


## Installation

Install the apps with kubectl

- Deployements
```bash
  cd Deployements
  kubectl apply -f ./my-manifest.yaml            # create resource(s)
  kubectl apply -f ./my1.yaml -f ./my2.yaml      # create from multiple files
  kubectl apply -f ./dir                         # create resource(s) in all manifest files in dir
```

- Services
```bash
  cd Services
  kubectl apply -f ./my-manifest.yaml            # create resource(s)
  kubectl apply -f ./my1.yaml -f ./my2.yaml      # create from multiple files
  kubectl apply -f ./dir                         # create resource(s) in all manifest files in dir
```
    
## Authors

- [@meisterveda](https://www.github.com/meisterveda)

  
## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

  
<!-- ## FAQ

#### Question 1

Answer 1

## Apps

- Heimdall
- Pi-hole
- Mist.io
- Code server
- Grafana
- Prometheus
- Naggio
- nextcloud
- plex
- pfsense
- zabbix
- home-assistant
- jenkins
- sonarr
- radarr -->