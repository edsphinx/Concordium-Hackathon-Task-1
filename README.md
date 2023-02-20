# Concordium Hackathon


## Condordium Mainnet Account Address 
* 3JSkNUDYEyGygnZkJAKsY7nNk6WHGJdmULHjAB9KHnhZnAdTH3


## Install Rust

#### First install rust with 
```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```

![rust1](https://github.com/edsphinx/Concordium-Hackathon-Task-1/blob/17664ca478ec59b89441e89ea1be82518f6a471a/Screen%20Shot%202023-02-20%20at%2012.13.08.png)

####  install Wasm which will be used for building contracts
```rustup target add wasm32-unknown-unknown```

![rust2](https://github.com/edsphinx/Concordium-Hackathon-Task-1/blob/76c126e67212b2614c0d14dae45bbd399bdb71b4/Screen%20Shot%202023-02-20%20at%2012.21.36.png)


## Install cargo-concordium

* Download cargo-condordium from https://developer.concordium.software/en/mainnet/net/installation/downloads-testnet.html#cargo-concordium-testnet
* Move and Rename file with ```mv cargo-concordium_2.7.0 /Users/edsphinx/.cargo/bin/cargo-concordium```

![cargo-condordium](https://github.com/edsphinx/Concordium-Hackathon-Task-1/blob/17664ca478ec59b89441e89ea1be82518f6a471a/Screen%20Shot%202023-02-20%20at%2012.27.53.png)


## Install Concordium-client

* Download condordium-client from https://developer.concordium.software/en/mainnet/net/installation/downloads-testnet.html#concordium-node-and-client-download-testnet
* Run the package and install
* to be able to run need to go to System Preferences → Security and unlock it with your password and click Allow Anyway.

![condordium-client](https://github.com/edsphinx/Concordium-Hackathon-Task-1/blob/17664ca478ec59b89441e89ea1be82518f6a471a/Screen%20Shot%202023-02-20%20at%2012.30.20.png)


## Install the Web Wallet

#### Install from https://chrome.google.com/webstore/detail/concordium-wallet/mnnkpffndmickbiakofclnpoiajlegmg/related?hl=en-US
 
![alt text](https://github.com/edsphinx/Concordium-Hackathon-Task-1/blob/17664ca478ec59b89441e89ea1be82518f6a471a/Screen%20Shot%202023-02-20%20at%2012.55.46.png)


## Create a Testnet account

#### Select Testnet on the begining to start process 

![alt text](https://github.com/edsphinx/Concordium-Hackathon-Task-1/blob/17664ca478ec59b89441e89ea1be82518f6a471a/Screen%20Shot%202023-02-20%20at%2012.56.52.png)


## Acquiring testnet CCD via the CCD faucet

#### from the same web wallet you request the Test tokens
 
![alt text](https://github.com/edsphinx/Concordium-Hackathon-Task-1/blob/17664ca478ec59b89441e89ea1be82518f6a471a/Screen%20Shot%202023-02-20%20at%2012.55.46.png)


## Export the account from web wallet and import it into concordium client

#### import into my wallet with
```concordium-client config account import 3fS4j4h1UPB7iEEuhx8jxXUk4Ze4y3ryf9sMRKQNbHAHfuvz6h.export --name edsphinx```
![alt text](https://github.com/edsphinx/Concordium-Hackathon-Task-1/blob/17664ca478ec59b89441e89ea1be82518f6a471a/Screen%20Shot%202023-02-20%20at%2012.59.16.png)


## And everything is ready
