[![Build Status](https://travis-ci.org/bitcabbage/bitwallet.svg?branch=master)](https://travis-ci.org/bitcabbage/bitwallet)

# Bitwallet
Bitwallet is a nice and sexy web service for working with Bitcabbage customer wallets.


## API
API is exposed through the following endpoint – 
> `https://quxze3zsll.execute-api.us-west-2.amazonaws.com/latest`

The endpoint is protected by the **authentication token**. The token must be provided via `x-api-key` header.

### Create new or get existing wallet for a customer 

> `POST /wallets`

Example body:

```json 
{
    customer: {
        id: "<SOME_CUSTOMER_ID>"
    }
}
```
  

## Setup instructions
In order to access Blockchain wallet via API, calling services' ip addresses must be provided in Wallet settings.

Current IP addresses are –

> 54.71.193.153

> 54.70.175.137