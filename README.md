# Introduction
This repository provides environments and templates to use example project
docker-compose-example.git with pkr.

# Get templates and set PKR_PATH

```bash
git clone git@gitlab.pclm.altair.com:pclm-team/pkr-demo.git
cd pkr-demo
```

# Create pkr kards and spawn environments

Development env

    pkr kard create dev -e dev

Production env

    pkr kard create prod -e prod

Test env

    pkr kard create test -e test

Spawn environment

    pkr kard make
    pkr up
