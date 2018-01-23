# etn-miner
Dockerfile for my etn-miner
# Usage

```
docker build -t stoertebeker2k/electroneum-miner .
docker run --name electroneum-miner --detach stoertebeker2k/electroneum-miner:latest --threads=8 --max-cpu-usage=100
```
