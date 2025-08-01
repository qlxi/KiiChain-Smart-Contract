# KiiChain-Smart-Contract
Before the workflow can successfully deploy the contract, several important steps must be completed:

    Setting up secrets in the GitHub repository

    Go to your repository settings: Settings > Secrets and variables > Actions

    Click New repository secret and add the following required secrets:

        RPC_URL:
        For the Kii testnet: https://json-rpc.uno.sentry.testnet.v3.kiivalidator.com/

        DEPLOYER_PRIVATE_KEY:
        The private key of the wallet used for deployment (in 0xabc123... format).
