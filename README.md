# Serverless Template for Golang

This repository contains template for creating serverless services written in Golang.

## Quick Start

1. Create a new service based on serverless-golang template

```
serverless create -u https://github.com/serverless/serverless-golang/ -p serverlessgopher
```

2. Compile function

```
cd serverlessgopher
GOOS=linux go build -o bin/main
```

3. Deploy!

```
serverless deploy
```
