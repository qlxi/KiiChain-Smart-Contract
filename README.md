## KiiChain Smart Contract

To allow the GitHub Actions workflow to deploy your KiiChain Smart Contract, you need to set up secrets in your repository:

1. Go to **Settings > Secrets and variables > Actions** in your GitHub repository.
2. Click **New repository secret** and add the following secrets:

   - **DEPLOYER_PRIVATE_KEY**  
     The private key of the wallet that will be used for deployment.  
     ⚠️ Make sure this is a testnet wallet and **never expose your private key in code**.

