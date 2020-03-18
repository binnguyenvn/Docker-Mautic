** Require
- Start traefik docker first
- https://github.com/binnguyenvn/Docker-treafik

** Config
- Edit .envs for DB infomations
- Edit production.yml for change domain infomation

** Start
- sudo docker stack deploy -c production.yaml mautic