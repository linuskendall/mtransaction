# mTransaction
TBD

## Architecture
TBD

## Server
Generate certificate:
```bash
make cert-server
```
Run:
```
make run-server
```

## Client
Generate certificate:
```bash
make cert-client cmd=req validator=Validator1
make cert-client cmd=sign
```

## Tester
TBD

## Development
Before building the rust server, you need:
```bash
# Ubuntu
apt update && apt upgrade -y
apt install -y protobuf-compiler libprotobuf-dev

# Alpine
apk add protoc protobuf-dev
```