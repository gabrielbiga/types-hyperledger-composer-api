# Types for Hyperledger Composer API Chaincode

This types library is referred to the Hyperledger Composer chaincode API (https://hyperledger.github.io/composer/latest/api/api-doc-index).
With these types you can build a chaincode using heavily typed Typescript interfaces.

# Installation
> `npm install --save types-hyperledger-composer-api`

And put the directory to your `includes` in `tsconfig.json`.
```json
    {
        ...
        "include": [
            ...
            "../node_modules/types-hyperledger-composer-api/*.ts"
            ...
        ]
        ...
    }
```

# Warning
This API is not complete yet. Pull requests are welcome! :grinning:

# License
MIT © Gabriel Matos
