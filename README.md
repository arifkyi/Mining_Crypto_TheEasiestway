# Mining_Crypto_TheEasiestway
MIning Monero with two commands

docker build . -t xmrig:rifky

Basic run:
docker run --name miner --rm -it xmrig:rifky


# Set up your own wallet and environment:

export POOL_URL="here, pool url"

export POOL_USER="Your public monero address"

export POOL_PASS="can be empty for some pool, other use that as miner id"

export DONATE_LEVEL="xmrig project donation in percent, default is 5"

# launch docker container after env setup
docker run --name miner --rm -it \
-e POOL_URL=$POOL_URL \
-e POOL_USER=$POOL_USER \
-e POOL_PASS="" \
xmrig:rifky
