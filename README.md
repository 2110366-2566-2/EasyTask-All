# EasyTask-All

A repo alias for EasyTask project (SE2 CU)
<br>
<br>

## Repository Locations

Since the repo is created outside this organization, we will forward you to our repository location.

<div align=center>

[<kbd> <br> Frontend <br> </kbd>][url1]
[<kbd> <br> Backend <br> </kbd>][url2]
[<kbd> <br> Infrastructure + Compose <br> </kbd>][url3]
  
</div>

[url1]: https://github.com/2110336-g8/EasyTaskFrontend
[url2]: https://github.com/2110336-g8/EasyTaskBackend
[url3]: https://github.com/2110336-g8/EasyTaskInfrastructure

## Link URLs

1. Frontend: [https://github.com/2110336-g8/EasyTaskFrontend](https://github.com/2110336-g8/EasyTaskFrontend)
2. Backend: [https://github.com/2110336-g8/EasyTaskBackend](https://github.com/2110336-g8/EasyTaskBackend)
3. Infrastructure + Docker compose files: [https://github.com/2110336-g8/EasyTaskInfrastructure](https://github.com/2110336-g8/EasyTaskInfrastructure)

## Deployment Instruction

1. Navigate to your deploymennt directory
2. Clone all repositories (frontend, backend, and infrastructure)
3. Configure all environment files
4. Configure reverse proxies, firewalls, and docker network (if needed)

## Deployment Directory Structure
```bash
(root)
├── backend-prod/
├── frontend-prod/
└── deploy/

(root)/deploy/
├── compose.backend.yaml
├── compose.frontend.yaml
├── compose.mongodb.yaml
├── compose.netdata.yaml
├── compose.wstest.yaml
├── compose.yaml
├── mongodb/
│   ├── db0_mongod.conf
│   └── mongod.conf
├── nginx/
│   ├── conf.d/
│   │   └── http/
│   │       └── easytask.vt.in.th.conf
│   └── nginx.conf
├── secrets/
└── websocket-test/

(root)/deploy/secrets/
├── app-env/
│   ├── .env.backend.dev
│   ├── .env.backend.prod
│   ├── .env.frontend.dev
│   ├── .env.frontend.prod
│   ├── rs256.key
│   └── rs256.key.pub
├── mongodb.dump
├── mongo.env
├── nginx-cert/
└── replica.key
```
