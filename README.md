# Mining_Crypto_TheEasiestway
MIning Monero with two commands

docker build . -t xmrig:rifky

Basic run:

<kbd>
 docker run --name miner --rm -it xmrig:rifky 
</kbd>



Theeereee, you already success mining the Crypto with XMR/Monero,
but that's for my account wallet.

For your wallet, follow below command

 Set up your own wallet and environment:

export POOL_URL="here, pool url"

export POOL_USER="Your public monero address"

export POOL_PASS="can be empty for some pool, other use that as miner id"

export DONATE_LEVEL="xmrig project donation in percent, default is 5"

eg like this:

<table>
 <tr><td>
export POOL_USER="8BWdDpi4uRyDL24XBMdQQFbiwTVAdUWpZAKTbHnqPUxoiL8je9hg1NDAow1BpVF5FsP6fFX847aQiQbGUhCZ32skDsH1Eu7" \ <br>
    POOL_PASS="" \ <br>
    POOL_URL="gulf.moneroocean.stream:20128" \ <br>
    DONATE_LEVEL=3 \ <br>
    PRIORITY=0 \ <br>
    THREADS=0
  </td></tr></table>


# launch docker container after env setup
docker run --name miner --rm -it \\ <br>
-e POOL_URL=$POOL_URL \\ <br>
-e POOL_USER=$POOL_USER \\ <br>
-e POOL_PASS="" \\ <br>
xmrig:rifky

# Monitor Your Mining

Depend to which pool

In this example i use this pool: pool.supportxmr.com:5555 <br>
then we use this web  https://supportxmr.com/

Open the web

then put YOUR wallet address that you use for Mining, then you can see the  there/there is one or more worker AFTER around 5 MINUTES

that means your mining is already run properly, CONGRATSSSZZZ

