# vault operator

> Operate the Vault clusters.
> More information: <https://developer.hashicorp.com/vault/docs/commands/operator>.

- Connect to a Vault server and initialize a new encrypted data store:

`vault operator init`

- Initialize the Vault server with a shared number of unseal keys, and a minimum to unseal:

`vault operator init -key-shares={{shares}} -key-threshold={{minimum}}`

- Unseal (unlock) the vault, by providing one of the key shares needed to access the encrypted data store:

`vault operator unseal {{unseal_key}}`

- Seal (lock) the Vault server, by removing the encryption key of the data store from memory:

`vault operator seal`
