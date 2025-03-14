
# APTOS QUEST 3

**Script for completing the 3rd Aptos quest on the Galxe platform**

## Features

-   Wapal Free Mint
    
-   Topaz Bidding
    
-   Mercato Free Mint
    
-   Mercato Bidding
    
-   Binding Twitter accounts with Galxe
    
-   Twitter Following
    

## Setup

```
git clone https://github.com/dao049/aptos-quest-3.git
cd aptos-quest-3
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

Fill in the following 4 files:

-   `files/accounts.txt` (private keys of the Aptos wallet) _required_
    
-   `files/twitters.txt` (auth_token from Twitter, can be obtained from cookies) _required_
    
-   `files/proxies.txt` (proxies in the format `username:password@ip:port`) _optional_
    
-   `files/evm.txt` - only fill in if you need to link Twitter to Galxe (private key of an EVM wallet) _optional_
    

## Run
