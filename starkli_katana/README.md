# starkli-katana

[Starkli](https://book.starkli.rs/) is the command line tool used to interact with Starknet nodes.
To work, starkli requires two files:

1. An account file, with account definition and public information.
2. A keystore file, with the encrypted private key of the user.

[Katana](https://book.dojoengine.org/toolchain/katana/overview.html) is a devnode made for Dojo, but extremely
useful to develop any smart contract.

In this repos, you can find `katana_account.json` and `katana_key.json`, which are the two
files already configured for the account #1 of default katana configuration.

To use them, it's recommended to use a `.env` file, to easily switch you configuration depending
on the network you want to target.
