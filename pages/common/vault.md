# vault

> Interact with HashiCorp Vault (cloud or self-hosted).
> Some subcommands such as `operator` have their own usage documentation.
> More information: <https://developer.hashicorp.com/vault/docs/commands>.

- Login the CLI client against the Vault server, prompts for a (hidden) token:

`vault login`

- List available secret engines:

`vault secrets list`

- Store a new secret in the vault, using the kv secret engine:

`vault kv put -mount {{secret}} {{keys_path}} {{key}}={{value}}`

- Store a new secret with a list of key values from a file:

`vault kv put -mount {{secret}} {{keys_path}} @{{path/to/file}}`

- Read values from the vault:

`vault kv get -mount {{secret}} {{keys_path}}`

- Read a specific field/key from the keys:

`vault kv get -mount {{secret}} -field {{field_name}} {{keys_path}}`

- Display help:

`vault {{[-h|--help]}}`
