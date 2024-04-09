# Litecoint-Core Docker
Docker wrapper to simplify management.
Based on official litecoin-core repo from https://github.com/litecoin-project/docker-litecoin-core/tree/master

## Start (`start.bat`)
```sh
docker compose up -d --build
```

## Stop (`stop.bat`)
```sh
docker compose down
```

### Ports
Mainnet
JSON-RPC/REST: `9332`
P2P: `9333`

Testnet
Testnet JSON-RPC: `19332`
P2P: `19335`

Regtest:
JSON-RPC/REST: `19443` (since 0.16+, otherwise 19332)
P2P: `19444`