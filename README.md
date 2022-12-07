# Mining_Crypto_TheEasiestway
MIning Monero with two commands

docker build . -t xmrig:rifky

Basic run:
docker run --name miner --rm -it xmrig:rifky


docker run --name miner --rm -it \
-e POOL_URL=$POOL_URL \
-e POOL_USER=$POOL_USER \
-e POOL_PASS="" \
xmrig:rifky
