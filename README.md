# Sample Serverless Golang App

This repository contains a simple serverless service written in Golang. An API gateway is automatically created through cloud formation(serverless yaml should have http event) 

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
