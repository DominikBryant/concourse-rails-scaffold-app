# Concourse Setup for Rails Scaffold App

## Install fly
```bash
install .fly /usr/local/bin
```

## Login
```bash
fly -t fh login --concourse-url http://192.168.1.3:8080
```

## Set Pipeline
```bash
fly set-pipeline -t fh -p scaffold-pipeline -c pipeline.yml
```
