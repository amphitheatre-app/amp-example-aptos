# amp-example-aptos

This is an example of using Aptos with AMP.

## Preparing

* Install AMP client: https://docs.amphitheatre.app/installation/cli/

* Update address in `Move.toml`

```toml
[addresses]
hello_blockchain='<YOUR-ACCOUNT>'
```

* Update private key in `.amp.toml`

```toml
[build.env]
BP_ENABLE_APTOS_DEPLOY = "true"
BP_APTOS_DEPLOY_PRIVATE_KEY = "<Your-Deploy-Private-Key>"
```

## Running

```bash
amp run
```

## Credits

Sample codes copied from https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/move-examples/my_first_dapp/move
