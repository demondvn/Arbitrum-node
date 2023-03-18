# Arbitrum-node

## Down snapshot
    cd /mnt/blockstore/arbitrum/
    axel -an 10 https://snapshot.arbitrum.io/mainnet/nitro.tar
    cd /mnt/blockstore/arbitrum/arb1/nitro/
    tar -xvf /mnt/blockstore/arbitrum/nitro.tar -C . 
## Run
    docker-compose up -d
## log
    docker-compose logs --follow
