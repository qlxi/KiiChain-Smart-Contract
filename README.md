# KiiChain-Smart-Contract
Перед тем как workflow сможет успешно выполнить деплой контракта, необходимо выполнить несколько важных шагов:

1. Настройка секретов в репозитории GitHub

    Перейдите в настройки вашего репозитория: Settings > Secrets and variables > Actions

    Нажмите New repository secret и добавьте следующие обязательные секреты:

        RPC_URL:
            Для тестовой сети Kii: https://json-rpc.uno.sentry.testnet.v3.kiivalidator.com/

        DEPLOYER_PRIVATE_KEY:
            Приватный ключ кошелька для деплоя (в формате 0xabc123...)
