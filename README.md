# dev-ops

```
.
├── app
│   └── volumes
└── infra
    └── volumes
        ├── kafka
        │   └── kafka-eagle
        ├── mysql
        │   └── docker-entrypoint-initdb.d
        ├── nginx
        │   ├── conf
        │   │   └── conf.d
        │   ├── html
        │   ├── logs
        │   └── ssl
        ├── ollama
        │   └── models
        │       ├── blobs
        │       └── manifests
        │           └── registry.ollama.ai
        │               └── library
        │                   ├── deepseek-r1
        │                   └── nomic-embed-text
        ├── open-webui
        ├── pgvector
        │   └── sql
        ├── rabbitmq
        └── redis
```

```
.
├── README.md
├── app
│   ├── .env
│   ├── .env.app.template
│   ├── docker-compose-app.yaml
│   └── volumes
│       └── app
└── infra
│   ├── .env
│   ├── .env.app.template
    ├── docker-compose-kafka-eagle.yaml
    ├── docker-compose-kafka.yaml
    ├── docker-compose-mysql.yaml
    ├── docker-compose-nginx.yaml
    ├── docker-compose-ollama.yaml
    ├── docker-compose-open-webui.yaml
    ├── docker-compose-pgadmin.yaml
    ├── docker-compose-pgvector.yaml
    ├── docker-compose-rabbitmq.yaml
    ├── docker-compose-redis-commander.yaml
    ├── docker-compose-redis.yaml
    ├── docker-compose-rocketmq.yaml
    ├── docker-compose-wordpress.yaml
    ├── docker-compose-xxl-job.yaml
    ├── docker-compose-zookeeper.yaml
    └── volumes
        ├── kafka
        │   └── kafka-eagle
        │       └── system-config.properties
        ├── mysql
        │   └── docker-entrypoint-initdb.d
        │       └── 0-init.sql
        ├── nginx
        │   ├── conf
        │   │   ├── conf.d
        │   │   │   └── default.conf
        │   │   └── nginx.conf
        │   ├── html
        │   │   ├── 50x.html
        │   │   └── index.html
        │   ├── logs
        │   └── ssl
        ├── ollama
        ├── open-webui
        ├── pgvector
        │   └── sql
        │       └── 0-init.sql
        ├── rabbitmq
        │   └── enabled_plugins
        └── redis
            └── redis.conf

22 directories, 26 files

```