# migration bitnami redmine to docker-redmine

* more info.
[]()

## Quick Start

* install `docker-compose`
* file copy to docker-host volume.


## do it.

* for create & start
```
docker-compose -f docker-redmine-config/docker-compose.production.yml up
```

* for create & start [deattach mode]
```
docker-compose -f docker-redmine-config/docker-compose.production.yml up -d
```

* for start
```
docker-compose -f docker-redmine-config/docker-compose.production.yml start
```

* for stop
```
docker-compose -f docker-redmine-config/docker-compose.production.yml stop
```

* for delete Containers
```
docker-compose -f docker-redmine-config/docker-compose.production.yml down
```
